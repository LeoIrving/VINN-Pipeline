Hi! This is an instruction for how to use VINN_pipeline :

>>PREREQUISITES :
	- Download VINN_pipeline.ipynb and change the path where the videofile folder and filelist.txt are at 7th cell
	- all your R3D files should be in the videofile folder
	- please list the name of all R3D files in filelist.txt separated by comma
	- Example: If you have "test1.r3d","test2.r3d" "test3.r3d" in the videofile, what you should have in folderfilelist.txt is "test1.r3d,test2.r3d,test3.r3d"

>>EXECUTE :
	- Run the code cell by cell
	- If you want visualization of camera trajactory, the code is provided in the last cell

>>OUTPUT :
	- The formated dataset is store in the folder named "runX" in the "All_val" folder for each video (X stands for the rank of the video been processed)
	- Please ignore the "test" folder

>> HOW TO EXPORT R3D FILE:
	- Record an RGB-D video by using Record3D app on iPhone
	- In the Library, choose the target video and export video as Sharable File (.r3d) by swipe left
	- Swipe left the target video again to share the file to your computer
	- Save the R3D file in the format mentioned in the prerequisites
		
