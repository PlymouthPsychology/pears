
Audio files
===============================

 

.. figure:: img/blanket.png
  :align: right
  :width: 50%


Some tips for use:

- Always use while sitting or lying down.  
- Make yourself comfortable with a pillow or cushion
- Keep warm with a blanket or cover
- Find a quiet place, and use headphones to avoid interruptions
  




Relaxation    
-------------


.. raw:: html

	<audio></audio>

	<ol class="playlist">
        

        <li>
          <a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/preparation.mp3">Preparing to relax</a>
        </li>

        <li>
        	<a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/Peaceful_Place.mp3">A peaceful place</a>
        </li>

        <li>
        	<a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/Progressive_Muscle_Relaxation.mp3">Progressive muscle relaxation</a>
        </li>

        <li>
        	<a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/Relaxed_Breathing.mp3">Deliberate, relaxed breathing</a>
        </li>

        <li>
        	<a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/Combined_Relaxation_Exercise.mp3">Combined relaxation (20 minutes).</a>
        </li>
      </ol>



Positive suggestions    
----------------------



.. raw:: html

	<ol class="playlist">
		
    <li>
      <a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/induction.mp3">Getting ready for positive suggestions</a>
    </li>

    <li>
			<a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/">Calm and pain free</a>
		</li>

		<li>
			<a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/">Strong and balanced</a>
		</li>

		<li>
      <a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/">Fluid movement</a>
    </li>


    <li>
      <a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/">Cool and soothing</a>
    </li>


    <li>
      <a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/">Nausea fading</a>
    </li>
	</ol>








.. note:: Some of these clips need editing down to make instructions consistent etc.








.. raw:: html

    <script>
      $(function() { 
        // Setup the player to autoplay the next track
        
        a = audiojs.createAll();
        audio = a[0];
        
        // Load in a track on click
        $('.playlist').find('li').click(function(e) {
          e.preventDefault();
          $(this).addClass('playing').siblings().removeClass('playing');
          audio.load($('a', $(this)).attr('data-src'));
          audio.play();
        });
       
      });
    </script>