# GBSC
**INTRODUCTION** 

 

GBS control is an improved GBS8200 RGB to VGA converter board, and an alternative firmware for Tvia Trueview5725 based upscales / video converter boards.

 

The firmware of this device is powered by gbs-control designed by ramapcsx2, used with permission under an open-source copyright.

https://github.com/ramapcsx2/gbs-control

 

Note: 

1. This device can not support composite and S-video signal. 

2. HDMI output and VGA output cannot work normally at the same time, you only need to keep one of them connecting. 

3. If you want to switch the video input signal (when you have more than one input video sources connecting into this device), you need to power off this device first. 

 

**FEATURES**

 

1. Almost zero latency.

2. Supports most of the retro video game consoles.

3. Supports RGBS, RGSB, RGBS SCART, RGBHV, Component, VGA input。

4. Supports RGBS, VGA, Component, HDMI Output.

5. Supports high-fidelity audio output.

6. Build in Si5351 stable clock generator.

7. Supports Video image adjustment.

8. Ability to balance the amplitude of the three primary color signals - R, G, B.

9. Supports Upscaling to 1080p. 

10. Supports Downscaling to 240p/288p (only output through Saturn A/V connector).

11. No synchronization loss switching 240p/480i, 288p/576i.

12. Supports resolutions (240p/288p/480i/480p/576i/576p/640p/720p/960p/1024p/1080p).

13. OLED screen and WIFI web configuration pages help you make the settings. 

14. Support firmware upgrade through micro-USB interface.

 

**SIGNAL INPUT AND OUTPUT INTRODUCTION** 

 

**Micro USB:**

It only supports firmware upgrade and cannot supply power for the normal working of this device. If you need to update the firmware, please see “Firmware Updates Guide”. 

 

 

**RGBS SYNC SELF-LOCKING BUTTON:**

When Press Down: Using an LM1881 chip to “strip” the sync information from composite video.

When the switch popped: by pass the composite signal.

 

**SYNC ON GREEN SELF-LOCKING BUTTON:** 

When the **Button** pressed down, this device can accept the VGA, RGBHV, RGSB signal. 

When the **Button** popped, this device can accept the RGBS and Component (YPbPr) signal. 

Note: 

When this **Button** pressed, this device can extract and use the sync signal attached to the Green signal, so the RGsB signal (such as the progressive scan mode on the retro game console) acceptable, but the “**SYNC ON GREEN** **SELF-LOCKING BUTTON** and the “**RGBS SYNC** **SELF-LOCKING BUTTON “** must be pressed simultaneously.

 

**POWER SELF-LOCKING BUTTON:**

The **Button** pressed down and this device is POWERED ON.

 

**DC 5V 2A:**

Connect a suitable 5V2A, 2.1 x 5.5mm PSU.

**Audio Output:**

Standard 3.5mm stereo headphone plugs type connector. Output high-fidelity audio.

 

**HDMI Output:**

Output HDMI digital signal. 

 

**RGBS/YPBPR OUTPUT (SATURN A/V CONNECTOR)**

If you want RGBS output (which must through the Saturn A/V connector), you need slide “RGBHV/RGBS SLIDE SWITCH” to the “RGBS” side.

If you want Component signal output through the Saturn A/V connector, you also need to turn on the “RGBHV/Component Toggle” in the web settings page.

![img](file:///C:/Users/ADMINI~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

**Note:**

 1. The **HDMI SLIDE SWITCH** much slide to “OFF” if you want to output RGBS/Component signal through the Saturn A/V connector

 2. The GBSC only output low resolution (240p/288p) RGBS signal through the Saturn A/V connector. 

 

**VGA OUTPUT**

Standard D-Sub15 (VGA) connector. 

**NOTE:** 

If you want to output VGA signal through this interface, The “HDMI SLIDE SWITCH” much slide to “OFF”.

 

**HDMI SLIDE SWITCH:**

Toggles the HDMI signal OFF and ON.

 

**RGBHV/RGBS SLIDE SWITCH:** 

If you want to output RGBS signal, please slide this switch to “RGBS” side. In other cases, please keep RGBHV by default.

**NOTE:** 

This function is used as RGBHV (VGA) to RGBS signal output, please SLIDE “**HDMI SLIDE SWITCH**” to OFF when using the RGBS output.

 

**SCART input:**

The European standard SCART interface can only receive RGBS signals. The less common Japanese JP21 SCART must be used with a converter.

 

**VGA input:**

Standard D-Sub15 (VGA) connector, accept the VGA and RGBHV signal, Can also receive RGsB signal. 

**NOTE:**

If you use this interface, you must press down the switch ”SYNC ON GREEN **SELF-LOCKING BUTTON**”

 

**Component input:**

Accept the Component (YPBPR) signal.

**NOTE****：**

The “SYNC ON GREEN **SELF-LOCKING BUTTON**” and “RGBS SYNC **SELF-LOCKING BUTTON**” much stays in popped.

 

**Audio INPUT:**

Left and right audio input.

 

**RGBS input:**

Accept the RGBS signal, I suggest you pressed on the “RGBS SYNC **SELF-LOCKING BUTTON**” to get a clean sync signal through the LM1881 chip when using the RGBS.

**NOTE****：**

If you are input a progressive scan RGBS signal (normally 480p or 576p), please keep press down these two switch at the same time. The “RGBS SYNC **SELF-LOCKING BUTTON**” and”SYNC ON GREEN **SELF-LOCKING BUTTON**”.

 

**RGB KNOB****：**

Adjust the red, green and blue signals intensity of the output images

 

**COMPATIBILITY MODE SLIDE SWITCH:**

Toggles compatibility mode ON and OFF

NOTE: The “Sega 32x/Neo Geo AES” console needs to slide to ON, and then restart GBSC to take effect; other consoles stay in OFF.
