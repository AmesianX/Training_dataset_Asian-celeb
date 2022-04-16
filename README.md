# Training_dataset_Asian-celeb
Data from the "trillionpairs.deepglint.com" site. The dataset consists of the crawled images of celebrities on the he web. 

-------------------------------------------------------------------------------------------
README: https://drive.google.com/file/d/1xTVBwoeNWiPS-KbH_6OFV32zME45_Z6q/view?usp=sharing

[Asian-celeb dataset]

- Training data(Asian-celeb)

The dataset consists of the crawled images of celebrities on the he web.The ima images are covered under a Creative Commons Attribution-NonCommercial 4.0 International license (Please read the license terms here. e. http://creativecommons.org/licenses/by-nc/4.0/).

-------------------------------------------------------------------------------------------
[train_msra.tar.gz]

MD5:c5b668f2204c400099b14f367069aef5

Content: Train dataset called MS-Celeb-1M-v1c with 86,876 ids/3,923,399 aligned images cleaned from MS-Celeb-1M dataset.

This dataset has been excluded from both LFW and Asian-Celeb.

Format: *.jpg

Google: https://drive.google.com/file/d/1aaPdI0PkmQzRbWErazOgYtbLA1mwJIfK/view?usp=sharing
-------------------------------------------------------------------------------------------
[msra_lmk.tar.gz]

MD5:7c053dd0462b4af243bb95b7b31da6e6

Content: A list of five-point landmarks for the 3,923,399 images in MS-Celeb-1M-v1c.

Format:      ..... 

while  is the path of images in tar file train_msceleb.tar.gz.

Label is an integer ranging from 0 to 86,875.

(x,y) is the coordinate of a key point on the aligned images.

left eye
right eye
nose tip
mouth left
mouth right

Google: https://drive.google.com/file/d/1FQ7P4ItyKCneNEvYfJhW2Kff7cOAFpgk/view?usp=sharing
-------------------------------------------------------------------------------------------
[train_celebrity.tar.gz]

MD5:9f2e9858afb6c1032c4f9d7332a92064

Content: Train dataset called Asian-Celeb with 93,979 ids/2,830,146 aligned images.

This dataset has been excluded from both LFW and MS-Celeb-1M-v1c.

Format: *.jpg

Google: https://drive.google.com/file/d/1-p2UKlcX06MhRDJxJukSZKTz986Brk8N/view?usp=sharing
-------------------------------------------------------------------------------------------
[celebrity_lmk.tar.gz]

MD5:9c0260c77c13fbb32692fc06a5dbfaf0

Content: A list of five-point landmarks for the 2,830,146 images in Asian-Celeb.

Format:      ..... 

while  is the path of images in tar file train_celebrity.tar.gz.

Label is an integer ranging from 86,876 to 196,319.

(x,y) is the coordinate of a key point on the aligned images.

left eye
right eye
nose tip
mouth left
mouth right

Google: https://drive.google.com/file/d/1sQVV9epoF_8jS3ge6DqbilpWk3UNE8U7/view?usp=sharing
-------------------------------------------------------------------------------------------
[testdata.tar.gz]

MD5:f17c4712f7562ea6d45f0a158e59b792

Content: Test dataset with 1,862,120 aligned images.

Format: *.jpg

Google: https://drive.google.com/file/d/1ghzuEQqmUFN3nVujfrZfBx_CeGUpWzuw/view?usp=sharing
-------------------------------------------------------------------------------------------
[testdata_lmk.tar]

MD5:7e4995eb9976a2cfd2b23db05d76572c

Content: A list of five-point landmarks for the 1,862,120 images in testdata.tar.gz.

Features should be extracted in the same sequence and with the same amount with this list.

Format:     ..... 

while  is the path of images in tar file testdata.tar.gz.

(x,y) is the coordinate of a key point on the aligned images.

left eye
right eye
nose tip
mouth left
mouth right

Google: https://drive.google.com/file/d/1lYzqnPyHXRVgXJYbEVh6zTXn3Wq4JO-I/view?usp=sharing
-------------------------------------------------------------------------------------------
[feature_tools.tar.gz]

MD5:227b069d7a83aa43b0cb738c2252dbc4

Content: Feature format transform tool and a sample feature file.

Format: We use the same format as Megaface(http://megaface.cs.washington.edu/) except that we merge all files into a single binary file.

Google: https://drive.google.com/file/d/1bjZwOonyZ9KnxecuuTPVdY95mTIXMeuP/view?usp=sharing
-------------------------------------------------------------------------------------------
