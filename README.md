### OpenCV: Open Source Computer Vision Library

[![Gittip](http://img.shields.io/gittip/OpenCV.png)](https://www.gittip.com/OpenCV/)

#### Resources

* Homepage: <http://opencv.org>
* Docs: <http://docs.opencv.org>
* Q&A forum: <http://answers.opencv.org>
* Issue tracking: <http://code.opencv.org>

#### Contributing

Please read before starting work on a pull request: <http://code.opencv.org/projects/opencv/wiki/How_to_contribute>

Summary of guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the coding style guide.

#### Things I broke in making the PPA

* Didn't forward-port any of the non-Linux, non-x64 patches
* Stripped out Java support
* Disabled compilation of samples/  ( BUILD_EXAMPLES=OFF in rules )
* The build-static-libs patch has been applied but there's a dependency problem
  so it's been neutered
* Added code to skip .AppleDouble directories when glob-adding paths & file
  in modules/
