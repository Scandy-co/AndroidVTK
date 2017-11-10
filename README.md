# Android VTK

Adopted from VTK NativeVTK and JavaVTK to be a 2 in 1.

## Configuring

Set `vtk.dir=` in `local.properties` to be a path where you have built VTK for Android. Namely the directory that has vtkConfig.cmake

In `build.gradle` set `ENABLE_JAVA_ACTIVITY` to be `true` or `false` to build a java activity or native activity.

## Building from command line

```bash
gradle app:assembleDebug
```
