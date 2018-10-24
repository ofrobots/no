
# Building

* [Install depot_tools](http://commondatastorage.googleapis.com/chrome-infra-docs/flat/depot_tools/docs/html/depot_tools_tutorial.html#_setting_up).
* Clone this repo: `git clone https://github.com/ofrobots/no && cd no`.
* Fetch dependencies: `gclient sync`.
* Generate build: `gn gen out`.
* Build using ninja: `ninja -C out`.

# FAQ

## Does this do anything?
No.