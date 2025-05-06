# SHARKonvnet
GPU CNN's for SHARK.

## Installation
* Cuda Toolkit https://developer.nvidia.com/cuda-downloads
* cuDNN https://developer.nvidia.com/cudnn
* SHARK http://image.diku.dk/shark/

## Makefile
* Here be hints on how to make it compile.

## MNIST
* Change directory to `scripts` and run `python prep_mnist_data.py`. This will download, unpack and normalize the MNIST dataset to `data/mnist/`.
* Change directory to the root of the project and run `make mnist`. This will compile `tests/MnistTest.cpp` into `obj/MnistTest.o`.
* Run with `./obj/MnistTest.o`. You should see some info about the convnet (specified in `tests/MnistTest.cpp`), and then some progress info every 500 itertation. After 2000 iterations the 01-loss should be around 4%. It converges to a little below 1%.

i have provided points to a file in the LibraGenX80/SHARKonvnet repository: tests/ConvNetTests.cpp in the master branch. Here's how you can proceed to work with it:


 `ConvNetTests.cpp` is located in the `tests` directory.
   - It likely contains test cases for the convolutional neural network functionality of the project.

2. **Access the File**:
   - Open the URL in your browser to review the file's code and structure.
   - If you have cloned the repository locally, navigate to the file path: `tests/ConvNetTests.cpp`.

3. **Typical Actions You Might Take**:
   - **Run Tests**: If the repository has a test framework set up, follow its documentation to execute the test cases.
   - **Modify Tests**: If you wish to add or update tests, edit the file locally, and commit changes.
   - **Debug or Improve**: Review the test cases for completeness, accuracy, and optimization opportunities.

4. **Contribute to the Repository**:
   - If you want to improve the file or add new tests, fork the repository, make your changes, and submit a pull request.

Would you like me to retrieve the file content for further analysis or help you explore any specific section of the file?