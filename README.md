# Lets-Transcribe-Defcon
Let's transcribe every single defcon talk and make them easily searchable by title, content, or author!

### Pipeline
1. Using the tldw project(I'm biased): https://github.com/rmusser01/tldw
2. Installing & Setting up the above project
3. Running it: 
	* Command used to archive and & Transcribe entirety of Defcon 7: `python summarize.py C:\Users\<USER>\Working\Conferences\Defcon-Conference-Links\Defcon7.txt -api cohere -k defcon7,infosec,hacking,conference -log DEBUG -wm distil-large-v3`
	* Command used to archive & Transcribe entirety of Defcon 8(In-progress): `python summarize.py C:\Users\GDesktop-1\Working\Conferences\Defcon-Conference-Links\Defcon8.txt -api cohere -k defcon8,infosec,hacking,conference -log DEBUG -wm distil-large-v3`













