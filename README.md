# FastAffineMotion
Official git for "Fast Affine Motion Estimation for Versatile Video Coding (VVC) Encoding"

# Paper
Fast Affine Motion Estimation for Versatile Video Coding (VVC) Encoding (Access, 2019)
Link: https://ieeexplore.ieee.org/abstract/document/8887438

# Revision history
2020-06-01: First uploaded the entire solution for the proposed method
See the macro "FAME_W_SKIP" and "FAME_W_UNIDIRECTION" in the source codes, particularly, EncCu.cpp and InterSearch.cpp files.

# Proposed Method for fast affine motion (As in the paper)
Entire solution for the proposed method written in C++ under VS2017: [ ](proposed_method)

The core part of the propsoed method is in [ ](proposed_method/source/Lib/EncoderLib/). Particulary, see "InterSearch.cpp"

Languague features: 
  * C++11
  * Supported Compilers: MS Visual Studio 2015/2017, GCC 5.4/7.3, Xcode/clang	

# Citation
S. Park and J. Kang, "Fast Affine Motion Estimation for Versatile Video Coding (VVC) Encoding," in IEEE Access, vol. 7, pp. 158075-158084, 2019, doi: 10.1109/ACCESS.2019.2950388.

@ARTICLE{8915688,
   author={S. {Park} and J. {Kang}},
   journal={IEEE Access},
   title={Fast Affine Motion Estimation for Versatile Video Coding (VVC) Encoding},
   year={2019},
   volume={7},
   number={},
   pages={158075 - 158084},
   doi={10.1109/ACCESS.2019.2950388},
   ISSN={2169-3536},
   month={},}

