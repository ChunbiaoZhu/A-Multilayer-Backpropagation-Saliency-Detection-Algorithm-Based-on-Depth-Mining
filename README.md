## A Multilayer Backpropagation Saliency Detection Algorithm Based on Depth Mining




|  ![CAIP 2017 logo][logo-caip] | Paper accepted at [ 17th International Conference on Computer Analysis of Images and Patterns (CAIP 2017)](https://www.cvl.isy.liu.se/CAIP2017.html)   |
|:-:|---|

[logo-caip]: https://github.com/ChunbiaoZhu/CAIP2017/blob/master/images/ystad.png "CAIP 2017 logo"


## Publication & Congratulations! 

This paper is selected as the [Sample Paper](http://www.springer.com/cda/content/document/cda_downloaddocument/9783319646978-c2.pdf?SGWID=0-0-45-1612625-p181071051) in [CAIP2017](https://www.springer.com/cn/book/9783319646978#otherversion=9783319646985)

The extended version " A multilayer backpropagation saliency detection algorithm and its applications " has been pubilshed in Multimed Tools Appl 2018. You can download in [here](https://link.springer.com/article/10.1007%2Fs11042-018-5780-4).


## Abstract
	
Saliency detection is an active topic in multimedia field. Several algorithms have been proposed in this field. Most previous works on saliency detection focus on 2D images. However, for some complex situations which contain multiple objects or complex background, they are not robust and their performances are not satisfied. Recently, 3D visual information supplies a powerful cue for saliency detection. In this paper, we propose a multilayer backpropagation saliency detection algorithm based on depth mining by which we exploit depth cue from three different layers of images. The evaluation of the proposed algorithm on two challenging datasets shows that our algorithm outperforms state-of-the-art.

## Framework
![QFramework saliency detection](https://github.com/ChunbiaoZhu/CAIP2017/blob/master/images/frame.png)




## Web Page
https://chunbiaozhu.github.io/CAIP2017/

## Code 

You can download our source code in [here](https://github.com/ChunbiaoZhu/CAIP2017/blob/master/CAIP_MB_CODE.zip).

How to use:

	1. Add test image to ./center_prior/Image/ and ./Image/, then run center_prior to get the center image in ./center_prior/center_results/.
	2. Add depth to ./Depth/, then run OURS1.m show the first layer result in ./OURS1/.
	3. Run OURS2.m, then get the second layer result in ./OURS2/.
	4. Run OURS.m, then get our final result in ./OURS/.

If you encounter an error, please restart MATLAB and re-run the code as described above.

If you have any question,please email us!

## Our results on Two Datasets
You can download our results on RGBD1_Dataset in [here](https://github.com/ChunbiaoZhu/CAIP2017/blob/master/CAIPRGBD2.zip).

You can download our results on RGBD2_Dataset in [here](https://github.com/ChunbiaoZhu/CAIP2017/blob/master/CAIPRGBD1.zip).

If you have any question,please email us!


## RGBD-PKU80 DATASET  【A new dataset is public in ICCVW 2017】

PKU80-Dataset is public.

You can download in [here](https://github.com/ChunbiaoZhu/TPPF/)


## Posterior work

If you were interested in this work, you may want to also check our posterior work, [ICCV2017](https://chunbiaozhu.github.io/ACVR2017/), which offers a novel idea.

If you were interested in this work, you may want to also check our posterior work, [MM2017](https://chunbiaozhu.github.io/MM2017/), which shows a novel application.

## Acknowledgements

This work was supported by the grant of National Natural Science Foundation of
China (No.U1611461), the grant of Science and Technology Planning Project of Guangdong
Province, China (No.2014B090910001), the grant of Guangdong Province Projects of
2014B010117007 and the grant of Shenzhen Peacock Plan (No.20130408-183003656).


## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/ChunbiaoZhu/CAIP2017/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:zhuchunbiao@pku.edu.cn>.

## Cite this paper as:
	1. Zhu C., Li G., Guo X., Wang W., Wang R. (2017) A Multilayer Backpropagation Saliency Detection Algorithm Based on Depth Mining. In: Felsberg M., Heyden A., Krüger N. (eds) Computer Analysis of Images and Patterns. CAIP 2017. Lecture Notes in Computer Science, vol 10425. Springer, Cham
	
	2. Chunbiao Zhu and Ge Li, A multilayer backpropagation saliency detection algorithm and its applications. Multimed Tools Appl (2018). https://doi.org/10.1007/s11042-018-5780-4

## Cite this paper as:
	1. @Inbook{Zhu2017,
	author="Zhu, Chunbiao
	and Li, Ge
	and Guo, Xiaoqiang
	and Wang, Wenmin
	and Wang, Ronggang",
	title="A Multilayer Backpropagation Saliency Detection Algorithm Based on Depth Mining",
	bookTitle="Computer Analysis of Images and Patterns: 17th International Conference, CAIP 2017, Ystad, Sweden, August 22-24, 		2017, Proceedings, Part II",
	year="2017",
	publisher="Springer International Publishing",
	address="Cham",
	pages="14--23",
	abstract="Saliency detection is an active topic in multimedia field. Several algorithms have been proposed in this field. Most previous works on saliency detection focus on 2D images. However, for some complex situations which contain multiple objects or complex background, they are not robust and their performances are not satisfied. Recently, 3D visual information supplies a powerful cue for saliency detection. In this paper, we propose a multilayer backpropagation saliency detection algorithm based on depth mining by which we exploit depth cue from four different layers of images. The evaluation of the proposed algorithm on two challenging datasets shows that our algorithm outperforms state-of-the-art.",
	isbn="978-3-319-64698-5",
	doi="10.1007/978-3-319-64698-5_2",
	url="https://doi.org/10.1007/978-3-319-64698-5_2"
	}



	2. @Article{Zhu2018,
	author="Zhu, Chunbiao
	and Li, Ge",
	title="A multilayer backpropagation saliency detection algorithm and its applications",
	journal="Multimedia Tools and Applications",
	year="2018",
	month="Mar",
	day="07",
	abstract="Saliency detection is an active topic in the multimedia field. Most previous works on saliency detection focus on 2D images. However, these methods are not robust against complex scenes which contain multiple objects or complex backgrounds. Recently, depth information supplies a powerful cue for saliency detection. In this paper, we propose a multilayer backpropagation saliency detection algorithm based on depth mining by which we exploit depth cue from three different layers of images. The proposed algorithm shows a good performance and maintains the robustness in complex situations. Experiments' results show that the proposed framework is superior to other existing saliency approaches. Besides, we give two innovative applications by this algorithm, such as scene reconstruction from multiple images and small target object detection in video.",
	issn="1573-7721",
	doi="10.1007/s11042-018-5780-4",
	url="https://doi.org/10.1007/s11042-018-5780-4"
	}









