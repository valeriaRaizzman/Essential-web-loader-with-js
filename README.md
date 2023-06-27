# Essential-web-loader-with-js

This is a simple web page that displays a blurry loading effect while an image is being loaded. The page gradually blurs the background image and updates the loading progress percentage until it reaches 100%. Once the image is fully loaded, the loading text disappears.



https://github.com/valeriaRaizzman/Essential-web-loader-with-js/assets/132442225/cbb0e577-894f-4540-aa49-782488ef1b6f




                                                  EXPLANATION / INNER WORKINGS

                  

* The inner workings of "Blurry Loading" is based on the JavaScript code in the script.js file. The process is explained step by step below:

* References to relevant HTML elements, such as loading text and background, are obtained using the querySelector method.

* The variable load is initialized with the value 0.

* A time interval is set using setInterval which calls the blurring function every 30 milliseconds.

* The blurring function runs at each time interval and does the following:

* Increase the load variable by 1.
* Checks if load has reached or exceeded the value 100. If so, the time interval is stopped using clearInterval, the loaded class is added to the document body, and the loading text is hidden.
* Updates the load text with the updated percentage (load).
* Calculate the opacity and blur of the background using the scale function.
* Applies the opacity and blur styles to the loading text and background respectively.
* The scale function performs a linear scale transformation to map one range of values ​​to another range. It is used to calculate the opacity and blur based on the load percentage.


                                                                USAGE

  

1. To use the "Blurry Loading" effect, please follow these steps:

2. Download the index.html, style.css, and script.js files to your local machine.

3. Place all the downloaded files in the same folder.

4. Open the index.html file using a compatible web browser.

5. You will see the "Blurry Loading" page displaying a blurry background image and a loading text.

6. As the page loads, the loading percentage will increase, and the background will gradually blur.

7. Once the loading is complete (reaches 100%), the loading text will disappear.



![Loader](Loader.png)
