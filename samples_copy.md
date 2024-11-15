---
layout: default
title: BridgeDiffusion
---

<div class="post">
	<h2 class="pageTitle">AVSync15 Demos</h2>
	<p>
For each of the 15 categories in the AVSync test set, we selected an example video to show the results of different generation methods.
    <br>
It is recommended to use earphones to hear the demos videos, raise the volume and zoom in the videos.
    </p>
</div>


<table border="0"> <!-- 表格边框设置为1 -->
	<!--<tr>Sample 1: Playing the flute.</tr>-->
    <tr> <!-- 表格的一行 -->
        <th style="width: 320px; font-size:20px">Input Image</th> <!-- 表头单元格 -->
 		<th style="width: 320px; font-size:20px">I2A+I2V (SVD+AudioLDM-v)</th> <!-- 表头单元格 -->
        <th style="width: 320px; font-size:20px">I2V2A (SVD+SeeingHearing)</th> <!-- 表头单元格 -->
    </tr>
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
    		<img src="./assets/video/baby_babbling_crying/sample_inputimage.jpg" width="330" style="max-width: 100%; height: auto;">
        </td>
		<td> <!-- 表格的单元格 -->
            <video width="330" height="240" controls>
                <source src="./assets/video/baby_babbling_crying/sample_svd+audioldmv.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video width="330" height="240" controls>
                <source src="./assets/video/baby_babbling_crying/sample_svd+seeing.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
	<tr> <!-- 表格的一行 -->
		<th style="width: 330px; font-size:20px" >I2A2V (AudioLDM-v+AVSyncD)</th> <!-- 表头单元格 -->
		<th style="width: 330px; font-size:20px">I2VA (CoDi)</th> <!-- 表头单元格 -->
        <th style="width: 330px; font-size:20px">I2VA (Ours)</th> <!-- 表头单元格 -->
    </tr>
    <tr> <!-- 表格的另一行 -->
		<td> <!-- 表格的单元格 -->
            <video width="320" height="240" controls>
                <source src="./assets/video/baby_babbling_crying/sample_audioldmv+avsyncd.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video width="320" height="240" controls>
                <source src="./assets/video/baby_babbling_crying/sample_codi.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video width="320" height="240" controls>
                <source src="./assets/video/baby_babbling_crying/sample_dualdit.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
</table>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>

<table border="0" width="400px" style="table-layout: fixed;"> <!-- 表格边框设置为1 -->
	<!--<tr>Sample 1: Playing the flute.</tr>-->
    <tr> <!-- 表格的一行 -->
        <th style="font-size:18px; font-weight: bold;"></th> <!-- 表头单元格 -->
 		<th style="font-size:18px; font-weight: bold;">I2A+I2V</th> <!-- 表头单元格 -->
        <th style="font-size:18px; font-weight: bold;">I2V2A</th> <!-- 表头单元格 -->
		<th style="font-size:18px; font-weight: bold;" >I2A2V</th> <!-- 表头单元格 -->
		<th style="font-size:18px; font-weight: bold;">I2VA</th> <!-- 表头单元格 -->
        <th style="font-size:18px; font-weight: bold;">I2VA</th> <!-- 表头单元格 -->
    </tr>
    <tr> <!-- 表格的一行 -->
        <th style="height:5px; font-size:15px">Input Image</th> <!-- 表头单元格 -->
 		<th style="height:5px; font-size:15px">SVD+AudioLDM-v</th> <!-- 表头单元格 -->
        <th style="height:5px; font-size:15px">SVD+SeeingHearing</th> <!-- 表头单元格 -->
		<th style="height:5px; font-size:15px">SVD+AVSyncD</th> <!-- 表头单元格 -->
		<th style="height:5px; font-size:15px">CoDi</th> <!-- 表头单元格 -->
        <th style="height:5px; font-size:15px">Ours</th> <!-- 表头单元格 -->
    </tr>
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
    		<img src="./assets/video/baby_babbling_crying/sample_inputimage.jpg" 
                 style="max-width: 100%; height: auto;">
        </td>
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/baby_babbling_crying/sample_svd+audioldmv.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/baby_babbling_crying/sample_svd+seeing.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/baby_babbling_crying/sample_audioldmv+avsyncd.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/baby_babbling_crying/sample_codi.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/baby_babbling_crying/sample_dualdit.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
</table>





<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>



<h4 class="pageTitle">Category 1: Baby babbling crying.</h4>







<table border="0" width="400px" style="table-layout: fixed;"> <!-- 表格边框设置为1 -->
	<!--<tr>Sample 1: Playing the flute.</tr>-->
    <tr> <!-- 表格的一行 -->
        <th style="font-size:18px; font-weight: bold;">IAV</th> <!-- 表头单元格 -->
 		<th style="font-size:18px; font-weight: bold;">I2A+I2V</th> <!-- 表头单元格 -->
        <th style="font-size:18px; font-weight: bold;">I2V2A</th> <!-- 表头单元格 -->
		<th style="font-size:18px; font-weight: bold;" >I2A2V</th> <!-- 表头单元格 -->
    </tr>
    <tr> <!-- 表格的另一行 -->
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/toilet_flushing/sample_svd+audioldmv.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/toilet_flushing/sample_svd+seeing.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/toilet_flushing/sample_audioldmv+avsyncd.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
		<td> <!-- 表格的单元格 -->
            <video height="120" controls>
                <source src="./assets/video/toilet_flushing/sample_audioldmv+avsyncd.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
</table>
