DotNet_AudioRenderer
=========
Small AudioRenderer for an easy access to the text to speech engine of windows and .Net.

## Intension:
This small piece of software allows for a fast and easy text to speech output as well as playing sounds through the .Net api interfaces.


## How to use:

--	TODO: build a small workflow


To define the standard culture of the voice to use, use the app.config file of your programm and add e.g.:

```
	<appSettings>
		<add key="DefaultCulture" value="en-US" />
	</appSettings>
```

The standard voice to use can be definded in the same way:

```
	<appSettings>
		<add key="StandardVoice" value="ScanSoft Steffi_Full_22kHz, ScanSoft Steffi_Dri40_16kHz" />
	</appSettings>
```

ATTENTION: The standard culture will override the standrd voice if it don't fit together.
ATTENTION: The project is only able to find voices of the same target plattorm type. This means if you compile it as x86 it is only able to find 32bit voices. If you compile it as x64 it is only able to identify 64bit voices.
	
### Example

--	TODO: build a small example

## ATTENTION!

This project is configured as a 32bit project. It can easily been compiled as x64 or mixed - but after doing so, the project is no longer able to find installed 32bit voices. So handle with care if you want to use your 32bit voices.

### Submodules
Keep attention to get and update all the embedded submodules. Sometimes it seems to be necessary to update the submodules' resources – do not submit this to the master branch of submodule

* Logger [TUD-INF-IAI-MCI/DotNet_Logger](https://github.com/TUD-INF-IAI-MCI/DotNet_Logger) - to log the audio output


## You want to know more?

--	TODO: build help from code doc

For getting a very detailed overview use the [code documentaion section](/Help/index.html) of this project.

