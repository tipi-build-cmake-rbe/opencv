## OpenCV: Open Source Computer Vision Library

### Build OpenCV with CMake RE

1. `git clone https://github.com/tipi-build-cmake-rbe/opencv.git`
2. `cd opencv/`
3. Ensure branch is `feature/cmake-re-4x` and origin is set to the aforementioned git clone url
4. `tipi build . -t linux-rbe -j64`

Head to http://127.0.0.1:8088/ to follow your build in a Web UI.

### Resources

* Homepage: <https://opencv.org>
  * Courses: <https://opencv.org/courses>
* Docs: <https://docs.opencv.org/4.x/>
* Q&A forum: <https://forum.opencv.org>
  * previous forum (read only): <http://answers.opencv.org>
* Issue tracking: <https://github.com/opencv/opencv/issues>
* Additional OpenCV functionality: <https://github.com/opencv/opencv_contrib> 


### Contributing

Please read the [contribution guidelines](https://github.com/opencv/opencv/wiki/How_to_contribute) before starting work on a pull request.

#### Summary of the guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the [coding style guide](https://github.com/opencv/opencv/wiki/Coding_Style_Guide).
