How to run

1. Navigate to \Dark Tower\imgui-master\examples\example_win32_opengl3
2. Run this
  mkdir -Force Debug
g++ -DUNICODE -I../.. -I../../backends main.cpp ../../backends/imgui_impl_opengl3.cpp ../../backends/imgui_impl_win32.cpp ../../imgui*.cpp -o Debug/example_win32_opengl3.exe --static -mwindows -lopengl32 -lgdi32 -ldwmapi

  .\Debug\example_win32_opengl3.exe
