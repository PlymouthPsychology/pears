Audio files for relaxation and positive suggestion
=======================================================

 

.. admonition:: Some tips for using these audio files

  - Always use while sitting or lying down.  
  - Make yourself comfortable with a pillow or cushion
  - Keep warm with a blanket or cover
  - Find a quiet place, and use headphones to avoid interruptions
  

.. container:: actionlink
  
  :doc:`You might also like this collection of soothing sounds and videos <calm-videos>`



Relaxation    
-------------

.. container:: gloss

  Some of these clips need editing down to make instructions consistent etc.


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






.. container:: gloss

  Additional suggestions might be included specifically for hips, and also for:

  - Reduced pain
  - Calmness and and contentment
  - Reduced nausea



.. raw:: html

	<ol class="playlist">
		
    <li>
      <a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/suggestion-introduction-knee.mp3">Getting ready for positive suggestions (2 mins)</a>
    </li>

    <li>
      <a href="#" data-src="http://plymouth-pears.s3.amazonaws.com/a-more-comfortable-knee.mp3">Make your knee more comfortable (10 mins)</a>
    </li>

	</ol>








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