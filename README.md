# Potato
A windows 10 themed skin for tkinter. Easy to use, Get rid of the old looking tkinter windows. Currently it supports only the windows platform, will add features for mac and linux soon.

All you need is that heema.py and run any of the test files, either test.py or test2.py, based on what kind of theme you like. 

Additional requirements: 

BlurWindow==1.2.1 (do pip install blurwindow)
tkextrafont
pillow

and it will work.




NEW FEATURES: 

#New Features

1) Title Bar:         title_bar=title_bar(root,text="Abhay")                  #you don't have to pack it, it's automatic :D Plus it's in darkmode , good for your eyes.
2) Menu Bar:          menu_bar=menu_bar(root)                                 #you don't have to pack it too, even this is automatic. :D
3) Menu Button:       menu_button1=menu_button(menu_bar, text="Edit")         #you don't have to pack it too, as these are menubar's buttons. :D
4) Left frame:        left_frame=left_frame(frame_name=root)                  #you don't have to pack it too, it's the left frame that gets packed to the left. :D
5) Leftframe Button:  b=left_frame_button(left_frame,text="Classic",command=lambda: apply_theme(root,classic)) 
		      b.configure(font=('calibri','12'))
		      #you don't have to pack it too, also you can configure all the buttons.
6)RightFrame: 				silimar to left_frame, replace left with right. 
7)RightFrame Button: 	similar  to left_frame_button, replace let with right.

#New Buttons

8)Button:						
	a=button(frame_name=root,text="Hello world",command=printer)
	a.pack(side=TOP)	#you need to pack this amazing button. A stylish button for tkinter. 	
	
	
							
											
											
											

											
##############			COMING SOON ♥

Tiles Buttons:	 			#Coming soon.
Routes: 				#Coming soon.
Splash Screens:				#Coming soon.
Dashboard: 				#Coming soon.

Feed Window:				#Coming soon.
Select Options:				#Coming soon.
New CheckBoxes: 			#Coming soon.

Description buttons: 			#Coming soon.
Tiles:					#Coming soon.
Splash Screens: 			#Coming soon.



#=================================================================		  	Help Needed					
New Sliders: 				#Coming soon.
User Dashboard:				#Coming soon.
Routes: 				#Coming soon. {easy, but I need a good logic that is easy to use.}






Upcoming new features that will make your apps stand out from the rest:


1) notification maker ✔
2) animate floating windows (not all will animate, like the menu pages) change the name to menu pages.
3) color modes, themes. ✔ (need more themes though windows api and ideas)
4) navigation ✔
5) change the page to menu_page ✔
6) complete the check box and select item
7) complete the searchbox with logic and click effects. 
8) support for videos 
9) support for images -_- ✔
10)proper format for making pages ✔
11) tiles and texts, if texts cross the width then use eclipes. 
12) at least a proper api for making apps. 
13) horizontal scrolling for tkinter apps. 
14) scrollbar with no scrollbar 
15) autohide scrollbar
16) Themes and color combinations.
17) bordered buttons 
18) animations+text animations
19) windows theme buttons, like back buttons, etc. ✔
20) card buttons (NEEDED, there are many examples of card buttons) that gives user more view about what is does, and also more information)
21) icon card label
22) rounded buttons
23) rounded window ✔
24) fix the auto pack features, add parameters to them, like left_frame, add kwargs.
25) use ctypes to access winapi's windowmanager to access the themes locally.
26) add support for dlls to support rounded corners on previous machines



























TODO: 

1) add credit for iconmoon for free font conversion for material icons.
2) from tkextrafont import Font (import this for new symbols/ use pyglet) 





2024. add ons and continuation.


lastClickX = 0
lastClickY = 0


def SaveLastClickPos(event):
    global lastClickX, lastClickY
    lastClickX = event.x
    lastClickY = event.y


def Dragging(event):

	
	x, y = event.x - lastClickX + window.winfo_x(), event.y - lastClickY + window.winfo_y()
	window.geometry("+%s+%s" % (x , y))




add this for windows movement through mouse tracking. u bind the events of the mouse with the position and done


#based on what version of window it is, make tkinter use it's original window with titlebar and use windows api to change its color. also add custom theme to it. 





