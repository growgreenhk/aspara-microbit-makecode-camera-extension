# aspara Microbit Makecode Camera Extension 

This is the micro:bit MakeCode Extension for controlling the asparaCamera by [Growgreen Limited](https://www.grow-green.com/)

<img src="./pngs/microbit.png" alt="image" width="200" height="auto">

## How to add aspara Microbit MakeCode Camera Extension to your MakeCode project

* Create/Open a MakeCode project using the micro:bit MakeCode Editor at https://makecode.microbit.org
* In the web editor, click on <B>"Extensions"</B> to add extensions to the project

    <img src="./pngs/proj_ext_b4.png" width=114 height="auto">

* Enter "<I><B>https://github.com/growgreenhk/aspara-microbit-makecode-camera-extension</B></I>" and search

    <img src="./pngs/proj_ext_search.png" width=889 height="auto">

* Select the <B>"aspara-microbit-makecode-camera-extension"</B> from the search results.

    <img src= "./pngs/proj_ext_result.png" width=144 height="auto">

* <B>"asparaCamera"</B> will show up in the editor and be ready to use.

    <img src="./pngs/proj_ext_complete.png" width=103 height="auto">

## How to use the extension
### On start - assign the UART Comm port "tx pin" and "rx pin"
* E.g. P0 to "tx pin" and P1 to "rx pin"

    <img src="./pngs/proj_tx_rx_pins.png" width=200 height="auto"/>

### Assign the asparaCamera to a feature mode.
* E.g. to the "Line Tracking" mode

    <img src="./pngs/proj_ext_select_mode.png" width="180" height="auto"/>

### Quit a feature mode
* Select "none" mode

    <img src="./pngs/proj_ext_select_none.png" width="120" height="auto"/>

### Get results
* Use the following block to get the feature result

    <img src="./pngs/proj_ext_get_results.png" width="220" height="auto"/>

* Wait for result ready, then get the result string or number

## Line Tracking
* Follow the line with specified color and return the line coordinates
* You could use the <B><I><span style="color: cyan;">"Line Tracking Select Color"</span></I></B> block or <B><I><span style="color: cyan;">"Line Tracking Set Color"</span></I></B> block to select your target color

    <img src="./pngs/proj_line_tracking_select_color.png" width="auto" height="80"/> <img src="./pngs/proj_line_tracking_select_predefined_color.png" width="auto" height="80">

* Demo: https://makecode.microbit.org/S82535-81900-19008-26073

## Color Tracking
* Follow the object with specified color and return the coordinates
* You could use the <B><I><span style="color: cyan;">"Color Tracking Select Color"</span></I></B> block or <B><I><span style="color: cyan;">"Color Tracking Set Color"</span></I></B> block to select your target color

    <img src="./pngs/proj_color_tracking_select_color.png" width="auto" height=80/> <img src="./pngs/proj_color_tracking_select_predefined_color.png" width = "auto" height=80>

* Demo: https://makecode.microbit.org/S24837-51094-76361-54804

## Object Detection
* General Oject detection and return the number of detected objects.

* Demo: https://makecode.microbit.org/S58563-16833-87646-54598

## Plant Diagnosis
* Detect the plant health and return the name of the planting problem

* Demo: https://makecode.microbit.org/S54546-52129-52097-99486

## Green/Red Lettuce Classification
* To detect the plant is Green lettuce or Red lettuce, and it returns "Green" or "Red"

* Demo: https://makecode.microbit.org/S57813-64135-25137-48434

## Object Classifcation
* General Object Classification and return the name of the detected object.

* Demo: https://makecode.microbit.org/S42923-67730-61115-17309

## Image Classification
* To detect the user labelled ojects on the display and return the label of the result.

* You could use the <B><I><span style="color: cyan;">"Capture Image with Label"</span></I></B> block to add an image on the display with the input label.

    E.g.

    <img src="./pngs/proj_image_classification_add_label.png" width = "auto" height=80>
    
    would add the image on the display with label "apple" when button "A" is pressed.

* You could use the <B><I><span style="color: cyan;">"Image Classfication Clear All Labels"</span></I></B> block to clear all labels.

    E.g.

    <img src="./pngs/proj_image_classification_clear_all_labels.png" width = "auto" height=80>
    
    would clear all labels when button "A+B" is pressed.

* Demo: https://makecode.microbit.org/S45171-11395-85226-25804

## Face Detection
* Detect how many faces on the display and return the number of faces.

* Demo: https://makecode.microbit.org/S41911-72788-99219-78181

## Facial Expression Detection
* Detect the facial expression on the display

* Demo: https://makecode.microbit.org/S47076-23103-19746-57899

## Custom Model Image classification
* Detect the custom objects in the user model

* Demo: https://makecode.microbit.org/S47076-23103-19746-57899
    * please consult [Using aspara Camera To Create Custom Image Classification Model With Teachable Machine](./docs/Using_aspara_Camera_To_Create_Custom_Image_Classification_Model_With_Teachable_Machine.md) to make your own models

## Scan Number
* Detect the numer 0 - 9 on the display

* Demo: https://makecode.microbit.org/S86583-57556-42878-36776

## Scan Alphabet
* Detect the numer A - Z, 0 - 9 on the display

* Demo: https://makecode.microbit.org/S08673-11210-13515-81797

## Scan QR/BarCode
* Detect any QR/Bar code on the display, then return the detected content

* Demo: https://makecode.microbit.org/S70205-94493-05894-36101

## Set WiFi Credentials
* Set the WiFi SSID and password

* Demo: https://makecode.microbit.org/S13281-72802-37846-52575

## Set Camera and Device Display Orientation Angles
* By setting the Camera and the Device LCD display Orientation Angles (0°, 90°, 180° or 270°), you could capture and display correctly with different device orientations.

## Take User Photo Demo
* Take a user photo and save to device

* Demo: https://makecode.microbit.org/S91673-02246-61208-06965

## Take Plant Photo Demo
* Take a planting photo on aspara Smart Grower

* Demo: https://makecode.microbit.org/S23513-65452-25410-30947
