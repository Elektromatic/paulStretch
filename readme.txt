C----------------------------------------------------------------------------
C  			          paulStretchDemo                
C----------------------------------------------------------------------------
C
C  This Pure Data patch uses the Paul stretch algorithm to time stretch musical
C  recordings.  It is suitable only for extreme sound stretching of the audio.
C
C  Please see http://hypermammut.sourceforge.net/paulstretch/ for a description 
C  of the Paul stretch algorithm.
C  
C  Please see https://soundcloud.com/get-ready-man/pure-data-paulstretch-demo
C  for an example of the use of this vanilla Pure Data patch.
C
C----------------------------------------------------------------------------
C  Requirements:   Pure Data <https://puredata.info/downloads/pure-data>
C----------------------------------------------------------------------------
C
Usage:  paulStretchDemo.pd is the parent patch. 
        bobFilter~.pd is a low pass filter with resonance.
        apfPhaser~.pd is a 12 stage all pass filter phaser.
	autopan.pd is an automatic stereo panning patch that uses the groupLFO patch.
        groupLFO.pd is a two source low frequency oscillator.

Contributing: Any contributions to this project are welcome.

Acknowledgements: I'd like to thank acreil for his pure data inspirations.