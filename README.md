# DefOS
Extra native OS functions for games written using the Defold game engine

Currently uses Native Extension for macOS and Windows. Contribute!

## Installation
You can use DefOS in your own project by adding this project as a [Defold library dependency](http://www.defold.com/manuals/libraries/). Open your game.project file and in the dependencies field under project add:

	https://github.com/subsoap/defos/archive/master.zip

## Methods

Use DefOS module methods via

```
function init(self)
	defos.disable_maximize_button()
	defos.disable_minimize_button()
	defos.disable_window_resize()
	defos.disable_mouse_cursor()
	defos.enable_mouse_cursor()
	defos.get_window_size()
	defos.set_window_size(10, 10, 800, 600)
	defos.set_window_title("I set this title using Defos")
	defos.toggle_maximize()
	defos.is_maximized()
	defos.toggle_fullscreen()
	defos.is_fullscreen()
	defos.on_mouse_enter(function ()
		print("Mouse entered window")
	end)
	defos.on_mouse_leave(function ()
		print("Mouse left window")
	end)
end
```
Use issues for feature requests.

## Example
An example is made using [DirtyLarry](https://github.com/andsve/dirtylarry)
![Defos example screenshot](https://user-images.githubusercontent.com/2209596/34541914-31af02fc-f0eb-11e7-9c16-a3088366c62d.jpg)
