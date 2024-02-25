# [go back to Overview](https://github.com/c4arl0s#ios-apps-using-objective-cuikit)

In order to update an existing Git submodule execute: (You might need permissions from Owner to get submodules)

```console
git submodule update --remote --merge
```

# [Hypnosister App - Objective-C](https://github.com/c4arl0s/6SubClassingUIView#1-creating-a-custom-view)

Hypnosister is an application that fills the screen with concentric circles, draw text and enable scrolling and zooming, it also uses the accelerometer to move this concentric circles. It changes color of the concentric circles using a shake motion detection.

| Notes                                                                                                                         |                                                                                                                               |                                                                                                                               | xcodeproj                                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://user-images.githubusercontent.com/24994818/124362615-98194800-dbfb-11eb-8f2a-350152c54935.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124362793-cd726580-dbfc-11eb-9001-4ed1e3836327.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124362644-df073d80-dbfb-11eb-834f-b225dcdc1831.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/123334887-59073a80-d509-11eb-8a80-01fcbb59e133.gif" width="250"> |

1. [x] [1. Creating a Custom View](https://github.com/c4arl0s/6SubClassingUIView#1-creating-a-custom-view)
2. [x] [2. The drawRect: method](https://github.com/c4arl0s/6SubClassingUIView#3-instantiating-a-uiview)
3. [x] [3. Instantiating a UIView](https://github.com/c4arl0s/6SubClassingUIView#3-instantiating-a-uiview)
4. [x] [4. Drawing Text and Shadows](https://github.com/c4arl0s/6SubClassingUIView#4-drawing-text-and-shadows)
5. [x] [5. Using UIScrollView](https://github.com/c4arl0s/6SubClassingUIView#5-using-uiscrollview)
6. [x] [6. Zooming](https://github.com/c4arl0s/6SubClassingUIView#6-zooming)
7. [x] [7. Hiding the Stabus bar](https://github.com/c4arl0s/6SubClassingUIView#7-hiding-the-stabus-bar)
8. [x] [8. Challenge: Colors](https://github.com/c4arl0s/6SubClassingUIView#8-challenge-colors)
9. [x] [9. For the More Curious: Retain Cycles](https://github.com/c4arl0s/6SubClassingUIView#9-for-the-more-curious-retain-cycles)
10. [x] [10. For the More Corious: Redrawing Views](https://github.com/c4arl0s/6SubClassingUIView#10-for-the-more-corious-redrawing-views)

# [7. ViewControllers (using MRC)](https://github.com/c4arl0s/7ViewControllers#7-viewcontrollers---objectivec---mrc)

| At a glance: Notes                                                                                                           |                                                                                                                              |                                                                                                                               |                                                                                                                               |
|------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://user-images.githubusercontent.com/24994818/91615856-1fe25600-e94a-11ea-8e2b-be5df5d79eb6.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/91620061-810f2700-e954-11ea-9ba2-90dc007a5eec.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/122389944-15c03100-cf37-11eb-8f0e-b769f9b9b98e.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124399491-73979b80-dce1-11eb-9e24-b9a4397090a9.png" width="250"> |

1. [x] [1. View Controllers and XIB Files](https://github.com/c4arl0s/7ViewControllers#1-view-controllers-and-xib-files)
2. [x] [2. Using View Controllers](https://github.com/c4arl0s/7ViewControllers#2-using-view-controllers)
3. [x] [3. Creating the UITabBarController](https://github.com/c4arl0s/7ViewControllers#3-creating-the-uitabbarcontroller)
4. [x] [4. Creating view controllers and tab bar items](https://github.com/c4arl0s/7ViewControllers#4-creating-view-controllers-and-tab-bar-items)
5. [x] [5. Creating views for the view controllers](https://github.com/c4arl0s/7ViewControllers#5-creating-views-for-the-view-controllers)
6. [x] [6. Demystifying the XIB: File's Owner](https://github.com/c4arl0s/7ViewControllers#6-demystifying-the-xib-files-owner)
7. [x] [7. Appearing and Disappearing Views](https://github.com/c4arl0s/7ViewControllers#7-appearing-and-disappearing-views)
8. [x] [8. The View Controller LifeCycle and Low-Memory Warnings](https://github.com/c4arl0s/7ViewControllers#8-the-view-controller-lifecycle-and-low-memory-warnings)
9. [x] [9. View Controllers Subclasses and Templates](https://github.com/c4arl0s/7ViewControllers#9-view-controllers-subclasses-and-templates)
10. [x] [10. Challenge: Map Tab](https://github.com/c4arl0s/7ViewControllers#10-challenge-map-tab)

# [8. The Accelerometer (Using MRC)](https://github.com/c4arl0s/8TheAccelerometer#8-the-accelerometer)

UIAccelerometer is deprecate. It was substitute with CoreMotion framework.

| At a glance: Notes                                                                                                           |                                                                                                                              |                                                                                                                              |                                                                                                                              |
|------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://user-images.githubusercontent.com/24994818/92413082-11e3c080-f114-11ea-9d21-f818f2e25ecd.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/92413176-80c11980-f114-11ea-8fa3-88d67a4a3e38.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/92771413-7b580f00-f360-11ea-8e92-f9517e530071.gif" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/93918672-4c338d00-fcd2-11ea-97cc-0e79f74c7760.gif" width="250"> |

1. [x] [1. Setting up the Accelerometer](https://github.com/c4arl0s/8TheAccelerometer#1-setting-up-the-accelerometer)
2. [x] [2. Getting Accelerometer Data](https://github.com/c4arl0s/8TheAccelerometer#3-orientation-and-scale-of-acceleration)
3. [x] [3. Orientation and Scale of Acceleration](https://github.com/c4arl0s/8TheAccelerometer#3-orientation-and-scale-of-acceleration)
4. [x] [4. Using Accelerometer Data](https://github.com/c4arl0s/8TheAccelerometer#4-using-accelerometer-data)
5. [x] [5. Smoothing Accelerometer Data](https://github.com/c4arl0s/8TheAccelerometer#5-smoothing-accelerometer-data)
6. [x] [6. Detecting Shakes](https://github.com/c4arl0s/8TheAccelerometer#6-detecting-shakes)
7. [x] [7. Challenge: Changing Colors](https://github.com/c4arl0s/8TheAccelerometer#7-challenge-changing-colors)
8. [x] [8. For the More Curious: Filtering and Frequency](https://github.com/c4arl0s/8TheAccelerometer#8-for-the-more-curious-filtering-and-frequency)
9. [x] [9. For the More Curious: Retina Display](https://github.com/c4arl0s/8TheAccelerometer#9-for-the-more-curious-retina-display)

### [End of Hypnosister App](https://github.com/c4arl0s/8TheAccelerometer#7-challenge-changing-colors) 
