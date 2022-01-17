# CMake_wxWidgets_template
Minimal cmake configurations to get stated with wxWidgets C++
<br/>
## 🔶 Get Started
<br/>

```bash
# Clone this project
$ git clone https://github.com/fidele000/CMake_wxWidgets_template --recursive

# If the repository was already cloned without submodules, use
$ git submodule update --init --recursive

# Enter project directory
$ cd cx_wxwidgets_template

# Generate projects files
$ mkdir build
$ cd build
$ cmake ..
```

### 💩 Linux Users must install OpenGL first
```bash
$ sudo apt-get update
$ sudo apt-get install libglu1-mesa-dev freeglut3-dev mesa-common-dev
```