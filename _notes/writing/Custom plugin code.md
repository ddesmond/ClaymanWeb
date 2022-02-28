---
title : Custom plugin code
notetype : feed
date : 22-02-2022
---
### Custom plugin code



from plugins.plugins_core import ClaymanPluginCore

class LoadMe(ClaymanPluginCore):
	def __init__(self):
        super(LoadMe, self)
        self.module_name = "LoadMe"
        self.module_version = "1.0"
        self.plugin_name = "Load me"

	def register(self):
        # Register you plugin here
        print("Registering {}".format(self.module_name))


    def process(self):
        print("LoadMe running")

def pass_plugin():
    return LoadMe()

def load_plugin():
    LoadMe().register()

def process_plugin():
    LoadMe().process()

def cleanup_plugin():
    LoadMe().cleanup()

