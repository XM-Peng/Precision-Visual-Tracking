# Precision-Visual-Tracking
This webpage hosts code, pretrained models, and some test samples associated with our paper Xiaoming Peng, et al., "Deep-learning-based Precision Visual Tracking", International Journal of Pattern Recognition and Artificial Intelligence, 37 (06), 2352008 (2023), https://doi.org/10.1142/S0218001423520080. 

For proprietary reasons, we only released the code necessary to test the tracking performance, the pretrained models, and two test image sequences with ground truth. The complete 480 image sequences used in this paper require a storage of about 20 GB, and we are still struggling to find a free space to host them. Also, the code and pretrained models can only be used for academic and teaching purposes, and must not be used for any commercial purposes.  

Disclaimer: THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

How to run the code: 
1) Download and organize all the folders and files properly on your local computer. The pretrained models and test data can be downloaded from https://drive.google.com/file/d/1g9f5FwjXd1zxAA9oQWIAhGvZr7atsrBa/view?usp=drive_link and https://drive.google.com/file/d/1o8lw1lGjLp8fQaJSjnunXHerPw2Yr3oY/view?usp=drive_link, respectively.
2) Reset settings.save_dir and settings.prj_dir in lib/test/evaluation/local.py.
3) Run demo.sh. The results will be saved to the Results folder under a test image sequence.

Big thanks: Some code of our software has been borrowed from ICLK, GLOCAL-Net, and STARK. 


