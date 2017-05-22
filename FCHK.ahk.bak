/* INFORMATION
FontCreator Hotkeys v.0.5.0 -- Keyboard shortcuts for FontCreator 11 Professional.
Copyright © 2017 Tyler Dickinson. Last modified 20/05/2017.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License in the README file for more details.

For questions, bug reports, comments, etc., submit an issue on GitHub: .
*/

; BEGIN SCRIPT

#NoEnv													; recommended for performance and compatibility with future AutoHotkey releases.
; #Warn													; enable warnings to assist with detecting common errors.
SendMode Input											; recommended for new scripts due to its superior speed and reliability.
CoordMode, Mouse, Client								; sets coordinate mode to client
SetWorkingDir %A_ScriptDir%								; ensures a consistent starting directory.
#IfWinActive, ahk_class TMainFormFontCreator			; restricts hotkeys to the FontCreator program
MsgBox "FontCreator Hotkeys has launched successfully!"	; informs user that the script is running
#EscapeChar \											; makes \ the escape character for this script, changed from the default `

														
														
/* CUSTOMIZING FCHK
A. It is not recommended to change hotkeys, as this can cause conflicts with other hotkeys or other functions within FontCreator.
B. To change hotkeys, find the hotkey you wish to change in the list below, and modify either the input key (first line of the sequence, before the ::), or the target destination (second line of the sequence).
C. To add new hotkeys, write the code in the space provided.
D. If you make any changes or add new hotkeys, ALWAYS copy and paste your changes (not the whole script, but only what you've changed) into a separate .txt file and save it. Otherwise, your changes WILL be lost when you install an updated version of FCHK. By saving your changes in a separate file, you can easily copy and paste them back into the code of an updated version of FCHK.
*/

;{ ADD NEW HOTKEYS HERE, AND CUSTOMIZE YOUR EXTERNAL APPLICATIONS HOTKEYS (see documentation)
; External applications
^+F10::
	Send 
return
^+F11::
	Send 
return
^+F12::
	Send 
return

; Other custom hotkeys

;}


;{ 1. File													
	$F1::													;{ default hotkey for help
		Send {F1}											; sends default hotkey
	Return													;}
	+F1::													;{ hotkey for launch manual
		Send {F10}hm										; target menu item
	return													;}
	^F1::													;{ hotkey for check for updates
		Send {F10}hu										; target menu item
	return													;}
	$^n::													;{ default hotkey for new project
		Send ^n												; sends default hotkey
	Return													;}
	$^o::													;{ default hotkey for open font/project
		Send ^o												; sends default hotkey
	Return													;}
	$^s::													;{ default hotkey for save
		Send ^s												; sends default hotkey
	Return													;}
	^+s::													;{ hotkey for save project as (formerly targeted save all)
		Send {F10}fj										; targets the menu item
	Return													;}
	^!s::													;{ reassigned hotkey for save all (formerly ctrl+shift+s)
		Send {F10}fv										; targets the menu item
	Return													;}
	$^p::													;{ default hotkey for print glyph/font/properties
		Send ^p												; sends default hotkey
	Return													;}
	$^i::													;{ default hotkey for open installed fonts
		Send ^i												; sends default hotkey
	Return													;}
	$^z::													;{ default hotkey for undo
		Send ^z												; sends default hotkey
	Return													;}
	$^+z::													;{ default hotkey for redo
		Send ^+z											; sends default hotkey
	Return													;}
	^y::													;{ reassigned hotkey for repeat (formerly ctrl+r; formerly targeted redo)
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 562, 50}								; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}
	!u::													;{ hotkey for used by
		Send +{F10}y										; targets the context menu item
	Return													;}
	$F10::													;{ defualt hotkey for activate main menu (=alt)
		Send {F10}											; sends default hotkey
	Return													;}
	$+F10::													;{ defualt hotkey for activate context menu (=right click)
		Send +{F10}											; sends default hotkey
	Return													;}
;}	
;{ 2. Validate and Export								
	!p::													;{ hotkey for validate font
		Send {F10}tv										; targets the menu item
	Return													;}			
	$F5::													;{ default hotkey for test font as TFF/OTF
		Send {F5}											; sends default hotkey
	Return													;}
	$^F5::													;{ default hotkey for test font as WOFF
		Send ^{F5}											; sends default hotkey
	Return													;}
	^e::													;{ hotkey for export settings (formerly targeted paste special)
		Send {F10}fe										; targets the menu item
	Return													;}
	$^+e::													;{ default hotkey for export as TFF/OTF
		Send ^+e											; sends default hotkey
	Return													;}
	$^+w::													;{ default hotkey for export as WOFF
		Send ^+w											; sends default hotkey
	Return													;}
	$^+a::													;{ default hotkey for export in all formats
		Send ^+a											; sends default hotkey
	Return													;}
	^!e::													;{ hotkey for export all
		Send {F10}fa										; targets the context menu item
	Return													;}
	^!i::													;{ hotkey for install font
		Send {F10}tn										; targets the menu item
	Return													;}			
;}	
;{ 3. Properties and Options								
	^k::													;{ hotkey for options (formerly targeted display values as hex)
		Send {F10}lo										; targets the menu item
	Return													;}
	$!Enter::												;{ default hotkey for font properties
		Send !{enter}										; sends default hotkey
	Return													;}
	!i::													;{ hotkey for font info
		Send {F10}ti										; targets the menu item
	Return													;}
	^6::													;{ hotkey for grid options
		Send {F10}lg										; targets the menu item
	Return													;}
	^7::													;{ hotkey for guide options
		Send {F10}ll										; targets the menu item
	Return													;}
	^8::													;{ hotkey for metrics options
		Send {F10}lm										; targets the menu item
	Return													;}
;}	
;{ 4. Externals											
	$^F10::													;{ default hotkey for launch MainType
		Send ^{F10}											; sends default hotkey
	Return													;}
	$^F11::													;{ default hotkey for launch Windows font folder
		Send ^{F11̂}											; sends default hotkey
	Return													;}
	$^F12::													;{ default hotkey for launch Windows character map
		Send ^{F12}											; sends default hotkey
	Return													;}
;}
;{ 5. Edit											
	$^c::													;{ default hotkey for copy
		Send ^c												; sends default hotkey
	Return													;}
	$^x::													;{ default hotkey for cut
		Send ^x												; sends default hotkey
	Return													;}
	$^v::													;{ default hotkey for paste
		Send ^v												; sends default hotkey
	Return													;}
	^+v::													;{ hotkey for paste special (formerly ctrl+alt+v and ctrl+e)
		Send {F10}es										; targets the menu item
	Return													;}
	$Del::													;{ default hotkey for delete
		Send {Del}											; sends default hotkey
	Return													;}
	$BS::													;{ default hotkey for clear selected glyphs
		Send {BS}											; sends default hotkey
	Return													;}
	^BS::													;{ hotkey for remove code points
		Send +{F10}r										; targets the context menu item
	Return													;}
	$Enter::												;{ default hotkey for open glyph edit
		Send {enter}										; sends default hotkey
	Return													;}
	^+c::													;{ hotkey for make simple
		Send {F10}em										; targets the menu item
	Return													;}			
	$^Del::													;{ default hotkey for make empty
		Send ^{Del}											; sends default hotkey
	Return													;}
	$^1::													;{ default hotkey for tag selected as "Important"
		Send ^1												; sends default hotkey
	Return													;}
	$^2::													;{ default hotkey for tag selected as "Incomplete"
		Send ^2												; sends default hotkey
	Return													;}
	$^3::													;{ default hotkey for tag selected as "Completed"
		Send ^3												; sends default hotkey
	Return													;}
	$^4::													;{ default hotkey for tag selected as "Review"
		Send ^4												; sends default hotkey
	Return													;}
	$^5::													;{ default hotkey for tag selected as "Workspace"
		Send ^5												; sends default hotkey
	Return													;}
	$p::													;{ default hotkey for load first 255 glyphs into preview
		Send p												; sends default hotkey
	Return													;}
	$+p::													;{ default hotkey for append first 255 glyphs to preview
		Send +p												; sends default hotkey
	Return													;}
;}	
;{ 6. Select												
	$^a::													;{ default hotkey for select all
		Send ^a												; sends default hotkey
	Return													;}
	^!a::													;{ hotkey for select composites
		Send {F10}eo										; targets the menu item
	Return													;}			
	$^t::													;{ default hotkey for invert selection
		Send ^t												; sends default hotkey
	Return													;}
	$^u::													;{ default hotkey for clear selection
		Send ^u												; sends default hotkey
	Return													;}
	^+1::													;{ hotkey for select tagged important
		Send {F10}eg{enter}									; targets the context menu item
	Return													;}
	^+2::													;{ hotkey for select tagged incomplete
		Send {F10}eg{Down 1}{enter}							; targets the context menu item
	Return													;}
	^+3::													;{ hotkey for select tagged completed
		Send {F10}eg{Down 2}{enter}							; targets the context menu item
	Return													;}
	^+4::													;{ hotkey for select tagged review
		Send {F10}eg{Down 3}{enter}							; targets the context menu item
	Return													;}
	^+5::													;{ hotkey for select tagged workspace
		Send {F10}eg{Down 4}{enter}							; targets the context menu item
	Return													;}
	$w::													;{ default hotkey for select next contour/point
		Send w												; sends default hotkey
	Return													;}
	$+w::													;{ default hotkey for select next contour/point with selected
		Send +w												; sends default hotkey
	Return													;}
	$q::													;{ default hotkey for select previous contour/point
		Send q												; sends default hotkey
	Return													;}
	$+q::													;{ default hotkey for select previous contour/point with selected
		Send +q												; sends default hotkey
	Return													;}
;}	
;{ 7. Visibility and Display								
	^9::													;{ reassigned hotkey for display values as hex (from ctrl+k)
		Send {F10}vyh										; targets the menu item
	Return													;}
	!9::													;{ reassigned hotkey for display values as dec (from ctrl+j)
		Send {F10}vyd										; targets the menu item
	Return													;}
	$h::													;{ default hotkey for hide everything except glyph
		Send h												; sends default hotkey
	Return													;}
	$^h::													;{ default hotkey for toggle fill outlines
		Send ^h												; sends default hotkey
	Return													;}
/* 	$p::													;{ default hotkey for toggle point/contour mode
 * 		Send p												; sends default hotkey
 * 	Return													;}
 */
	!1::													;{ hotkey for automatic captions
		Send +{F10}na										; targets the context menu item
	Return													;}
	!2::													;{ hotkey for glyph name captions
		Send +{F10}ng										; targets the context menu item
	Return													;}
	!3::													;{ hotkey for glyph index captions
		Send +{F10}ni										; targets the context menu item
	Return													;}
	!4::													;{ hotkey for codepoint captions
		Send +{F10}nc										; targets the context menu item
	Return													;}
	!5::													;{ hotkey for unicode name captions
		Send +{F10}nu										; targets the context menu item
	Return													;}
;}
;{ 8. Zoom												
	z::														;{ hotkey for zoom in selector tool
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 383, 90}								; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	!z::													;{ hotkey for zoom to selected
		Send {F10}vz										; targets the menu item
	Return													;}
	$=::													;{ default hotkey for increase cell size/zoom in
		Send =												; sends default hotkey
	Return													;}
	$^=::													;{ default hotkey for increase cell size/zoom in
		Send ^=												; sends default hotkey
	Return													;}
	$^+=::													;{ default hotkey for increase character size
		Send ^+=											; sends default hotkey
	Return													;}
	$-::													;{ default hotkey for decrease cell size/zoom out
		Send -												; sends default hotkey
	Return													;}
	$^-::													;{ default hotkey for decrease cell size/zoom out
		Send ^-												; sends default hotkey
	Return													;}
	$^+-::													;{ default hotkey for decrease character size
		Send ^+-											; sends default hotkey
	Return													;}
	$/::													;{ default hotkey for fit to window
		Send /												; sends default hotkey
	Return													;}
	$^0::													;{ default hotkey for reset zoom to default
		Send ^0												; sends default hotkey
	Return													;}
;}	
;{ 9. Navigation											
	$^Tab::													;{ default hotkey for next window/tab
		Send ^{Tab}											; sends default hotkey
	Return													;}
	$^+Tab::												;{ default hotkey for previous tab/window
		Send ^+{Tab}										; sends default hotkey
	Return													;}
	$^F4::													;{ default hotkey for close tab
		Send ^{F4}											; sends default hotkey
	Return													;}
	$^w::													;{ default hotkey for close window
		Send ^w												; sends default hotkey
	Return													;}
	$^f::													;{ default hotkey for find
		Send ^f												; sends default hotkey
	Return													;}
	$F3::													;{ default hotkey for find next
		Send {F3}											; sends default hotkey
	Return													;}
	$+F3::													;{ default hotkey for find previous
		Send +{F3}											; sends default hotkey
	Return													;}
	$!Left::												;{ default hotkey for previous glyph
		Send !{Left}										; sends default hotkey
	Return													;}
	$!Right::												;{ default hotkey for next glyph
		Send !{Right}										; sends default hotkey
	Return													;}
;}
;{ 10. Grids, Guidelines, and Anchors					
	$g::													;{ default hotkey for add guideline through selected point
		Send g												; sends default hotkey
	Return													;}
	+g::													;{ hotkey for toggle grid
		Send {F10}vg										; targets the menu item
	Return													;}			
	!+g::													;{ hotkey for toggle snap to grid
		Send {F10}vp										; targets the menu item
	Return													;}
	^g::													;{ hotkey for toggle guidelines
		Send {F10}vu										; targets the menu item
	Return													;}			
	^!g::													;{ hotkey for toggle snap to guidelines
		Send {F10}vn										; targets the menu item
	Return													;}
	!g::													;{ hotkey for toggle lock guides
		Send {F10}vl										; targets the menu item
	Return													;}			
	!a::													;{ hotkey for add anchor
		Send +{F10}n										; targets the context menu item
	Return													;}											
	!+a::													;{ hotkey for toggle anchor visibility
		Send {F10}va										; targets the menu item
	Return													;}
	^!+a::													;{ hotkey for lock anchors
		Send {F10}vk										; targets the menu item
	Return													;}
	!^m::													;{ hotkey for toggle metrics visibility
		Send {F10}vm										; targets the menu item
	Return													;}
	^!+m::													;{ hotkey for lock metrics
		Send {F10}ve										; targets the menu item
	return													;}
;}	
;{ 11. Arrange											
	PgUp::													;{ hotkey for bring forward
		Send +{F10}of										; targets the menu item
	Return													;}			
	+PgUp::													;{ hotkey for bring to front
		Send +{F10}ot										; targets the menu item
	Return													;}			
	PgDn::													;{ hotkey for send backward
		Send +{F10}ob										; targets the menu item
	Return													;}			
	+PgDn::													;{ hotkey for send to back
		Send +{F10}ok										; targets the menu item
	Return													;}			
	!l::													;{ hotkey for align left
		Send +{F10}bl										; targets the menu item
	Return													;}			
	!e::													;{ hotkey for align center
		Send +{F10}bc										; targets the menu item
	Return													;}			
	!r::													;{ hotkey for align right
		Send +{F10}br										; targets the menu item
	Return													;}			
	!t::													;{ hotkey for align top
		Send +{F10}bt										; targets the menu item
	Return													;}			
	!m::													;{ hotkey for align middle
		Send +{F10}bm										; targets the menu item
	Return													;}			
	!b::													;{ hotkey for align bottom
		Send +{F10}bb										; targets the menu item
	Return													;}			
	!h::													;{ hotkey for distribute horizontally
		Send +{F10}bh										; targets the menu item
	Return													;}			
	!v::													;{ hotkey for distribute vertically
		Send +{F10}bv										; targets the menu item
	Return													;}			
;}	
;{ 12. Color (known issue)												
	$c::													;{ default hotkey for toggle standard/color mode
		Send c												; sends default hotkey
	Return													;}
	+l::													;{ hotkey for colorize
		Send +{F10}z										; targets the context menu item
	Return													;}			
	^+l::													;{ hotkey for add color layer
		Send +{F10}a										; targets the context menu item
	Return													;}			
	!+l::													;{ hotkey for decolorize GEW
		Send +{F10}cd										; targets the context menu item
	Return													;}			
	!b::													;{ hotkey for colorize to selected color
		Send +{F10}oc										; targets the context menu item
	Return												;}	
	/* Issues
	1. Cannot combine with glyph edit window hotkey for decolorize; GEW send sequence conflicts with font overview window Copy command; FOW send sequence conflicts with GEW Order command.
	xx::													;{ hotkey for decolorize FOW
		Send +{F10}od										; targets the context menu item
	Return												;}	
	*/
;}	
;{ 13. Transform										
	$F6::													;{ default hotkey for glyph transformer wizard
		Send {F6} 											; sends default hotkey
	Return													;}
	+m::													;{ hotkey for autometrics
		Send {F10}la										; targets the menu item
	Return													;}			
	+k::													;{ hotkey for autokern
		Send {F10}lk										; targets the menu item
	Return													;}			
	o::														;{ hotkey for optimize contours
		Send {F10}ez										; targets the menu item
	Return													;}			
	!d::													;{ hotkey for change direction
		Send {F10}eh										; targets the menu item
	Return													;}			
	^j::													;{ hotkey for contour union
		Send {F10}eju										; targets the menu item
	Return													;}			
	!j::													;{ hotkey for contour intersection
		Send {F10}eji										; targets the menu item
	Return													;}			
	^!j::													;{ hotkey for contour exclusion
		Send {F10}eje										; targets the menu item
	Return													;}			
	,::														;{ hotkey for rotate ccw
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 1300, 90}								; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	.::														;{ hotkey for rotate cc
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 1338, 90}								; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	+,::													;{ hotkey for flip
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 1224, 90}								; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	+.::													;{ hotkey for mirror
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 1265, 90}								; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	s::														;{ hotkey for smooth and align curves
		Send +{F10}v										; targets the context menu item
	Return													;}
	+s::													;{ hotkey for smooth curves (point mode), split self intersecting (contour mode)
		Send +{F10}s										; targets the context menu item
	Return													;}			
	x::														;{ hotkey for extend corner
		Send +{F10}e										; targets the context menu item
	Return													;}			
	+x::													;{ hotkey for split contour
		Send +{F10}l										; targets the context menu item
	Return													;}			
	+/::													;{ hotkey for round xy coordinates
		Send +{F10}x										; targets the context menu item
	Return													;}
	$n::													;{ default hotkey for change point to on-curve
		Send n												; sends default hotkey
	Return													;}
	$f::													;{ default hotkey for change point to off-curve
		Send f												; sends default hotkey
	Return													;}
	!q::													;{ hotkey for convert to quadratic
		Send {F10}e{Up 8}{Right}q							; targets the context menu item
	Return													;}			
	!+q::													;{ hotkey for convert to cubic
		Send {F10}e{Up 8}{Right}c							; targets the context menu item
	Return													;}			
;}	
;{ 14. Tools												
	v::														;{ hotkey for selection tool
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 25, 90}									; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	+v::													;{ hotkey for freehand selection tool
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 61, 90}									; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	r::														;{ hotkey for rectangle tool
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 820, 90}								; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	l::														;{ hotkey for elipse tool
		MouseGetPos, xpos, ypos								; identifies the mouse starting position
		Send {click 860, 90}								; clicks the button
		MouseMove, %xpos%, %ypos%, 0						; returns the mouse immediately to the starting position
	Return													;}			
	d::														;{ hotkey for draw contour
		Send {F10}ic										; targets the menu item
	Return													;}			
	+d::													;{ hotkey for free draw contours
		Send {F10}if										; targets the menu item
	Return													;}			
	$k::													;{ default hotkey for knife
		Send k												; sends default hotkey
	Return													;}
	$m::													;{ default hotkey for measure
		Send m												; sends default hotkey
	Return													;}
	$b::													;{ default hotkey for paint bucket
		Send b												; sends default hotkey
	Return													;}
;}	
;{ 15. Toolbars and Panels								
	$F2::													;{ default hotkey for user notes
		Send {F2}											; sends default hotkey
	Return													;}
	$+F2::													;{ default hotkey for palette
		Send +{F2}											; sends default hotkey
	Return													;}
	$F4::													;{ default hotkey for glyph properties
		Send {F4}											; sends default hotkey
	Return													;}
	$+F4::													;{ default hotkey for anchors
		Send +{F4}											; sends default hotkey
	Return													;}
	$F7::													;{ default hotkey for glyph validation
		Send {F7}											; sends default hotkey
	Return													;}
	$+F7::													;{ default hotkey for toggle status bar
		Send +{F7}											; sends default hotkey
	Return													;}
	$^l::													;{ default hotkey for toggle categories/scripts panel
		Send ^l												; sends default hotkey
	Return													;}
	$F8::													;{ default hotkey for preview
		Send {F8}											; sends default hotkey
	Return													;}
	$+F8::													;{ default hotkey for members
		Send +{F8}											; sends default hotkey
	Return													;}
	$^F8::													;{ default hotkey for OpenType Designer/code editor
		Send ^{F8}											; sends default hotkey
	Return													;}
	$F9::													;{ default hotkey for background image
		Send {F9}											; sends default hotkey
	Return													;}
	$F11::													;{ default hotkey for comparison
		Send {F11}											; sends default hotkey
	Return													;}
	$F12::													;{ default hotkey for samples
		Send {F12}											; sends default hotkey
	Return													;}
;}
;{ 16. Create											
	!c::													;{ hotkey for insert character
		Send {F10}ia										; targets the menu item
	Return													;}			
	+c::													;{ hotkey for insert glyph
		Send {F10}is										; targets the menu item
	Return													;}			
	!+c::													;{ hotkey for insert composite glyph
		Send {F10}ig										; targets the menu item
	Return													;}			
	^!c::													;{ hotkey for complete composites
		Send {F10}ei										; targets the menu item
	Return													;}			
	^d::													;{ hotkey for import image
		Send {F10}li										; targets the menu item
	Return													;}			
	+f::													;{ hotkey for insert point
		Send {F10}ip										; targets the menu item
	Return													;}
	$a::													;{ default hotkey for add point(s) after selected
		Send a												; sends default hotkey
	Return													;}
	^!1::													;{ hotkey for automatic glyph type
		Send +{F10}y{enter}									; targets the context menu item
	Return													;}
	^!2::													;{ hotkey for unassigned glyph type
		Send +{F10}y{down}{enter}							; targets the context menu item
	Return													;}
	^!3::													;{ hotkey for simple glyph type
		Send +{F10}y{down 2}{enter}							; targets the context menu item
	Return													;}
	^!4::													;{ hotkey for ligature glyph type
		Send +{F10}y{down 3}{enter}							; targets the context menu item
	Return													;}
	^!5::													;{ hotkey for mark glyph type
		Send +{F10}y{down 4}{enter}							; targets the context menu item
	Return													;}
	^!6::													;{ hotkey for component glyph type
		Send +{F10}y{down 5}{enter}							; targets the context menu item
	Return													;}
;}	
;{ 17. OpenType Designer (empty)									

;}
;{ 18. Mouse (need to complete)												
/* 	$::													;{ default hotkey for 
		Send 											; sends default hotkey
	Return													;}
	$::													;{ default hotkey for 
		Send 											; sends default hotkey
	Return													;}
	$::													;{ default hotkey for 
		Send 											; sends default hotkey
	Return													;}
	$::													;{ default hotkey for 
		Send 											; sends default hotkey
	Return													;}
	$::													;{ default hotkey for 
		Send 											; sends default hotkey
	Return													;}
	$::													;{ default hotkey for 
		Send 											; sends default hotkey
	Return													;} */
	;}
;{ 19. Palette (empty)											

;}
;{ 20. Validator Window (empty)									

;}
;{ 21. Anchors Toolbar (empty)									

;}
;{ 22. Members Toolbar (empty)									

;}
;{ 23. Glyph Transformation Toolbar (empty)						

;}
;{ 24. Autometrics Wizard (empty)								

;}
;{ 25. Autokern Wizard (empty)									

;}