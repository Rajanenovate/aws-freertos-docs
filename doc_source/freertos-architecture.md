# Amazon FreeRTOS Architecture<a name="freertos-architecture"></a>

Amazon FreeRTOS is intended for use on embedded microcontrollers\. It is typically flashed to devices as a single compiled image with all the components required for the device application\. This image combines functionality for the application written by the embedded developer, software libraries provided by Amazon, the FreeRTOS kernel, and drivers and board support packages \(BSPs\) for the hardware platform\. Independent of the individual microcontroller being used, embedded application developers can expect the same standardized interfaces to the FreeRTOS kernel and all Amazon FreeRTOS software libraries\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/freertos/latest/userguide/images/architecture.png)