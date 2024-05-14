# POS: A Prompts Optimization Suite for Augmenting Text-to-Video Generation

This repository is a display of the results of POS[Paper ID 6768].

## Results comparison with good and bad initial noise
### Model Scope
<table class="center">
<tr>
  <td style="text-align:center;"colspan="4"><b>Bad initial noise</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/bn_dog.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/bn_elephant.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/11_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/121_woPOS.gif"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">A dog wearing a Superhero outfit with red cape flying through the sky</td>
  <td width=25% style="text-align:center;">3D model of an elephant origami. Studio lighting</td>
  <td width=25% style="text-align:center;">A girl is singing among the flowers</td>
  <td width=25% style="text-align:center;">A woman is doing yoga in the sunset</td>
</tr> -->
  
<tr>
  <td style="text-align:center;"colspan="4"><b>Good initial noise</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/gn_dog.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/gn_elephant.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/11_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/12_wPOS.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">A dog wearing a Superhero outfit with red cape flying through the sky</td>
  <td width=25% style="text-align:center;">3D model of an elephant origami. Studio lighting</td>
  <td width=25% style="text-align:center;">A girl is singing among the flowers</td>
  <td width=25% style="text-align:center;">A woman is doing yoga in the sunset</td>
</tr>
</table>


## Video qualitative results
### Real-World Videos(ModelScope)
<table class="center">
<tr>
  <td style="text-align:center;"colspan="4"><b>Without POS</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/1_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/10_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/11_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/121_woPOS.gif"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">A man is speaking in front of the blackboard</td>
  <td width=25% style="text-align:center;">A couple is watching the sunset on the lawn</td>
  <td width=25% style="text-align:center;">A girl is singing among the flowers</td>
  <td width=25% style="text-align:center;">A woman is doing yoga in the sunset</td>
</tr> -->

<tr>
  <td style="text-align:center;"colspan="4"><b>With POS</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/1_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/10_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/11_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/12_wPOS.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">A man is speaking in front of the blackboard</td>
  <td width=25% style="text-align:center;">A couple is watching the sunset on the lawn</td>
  <td width=25% style="text-align:center;">A girl is singing among the flowers</td>
  <td width=25% style="text-align:center;">A woman is doing yoga in the sunset</td>
</tr>
</table>

### UnReal-World Videos(ModelScope)
<table class="center">
<tr>
  <td style="text-align:center;"colspan="4"><b>Without POS</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/2_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/3_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/4_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/9_woPOS.gif"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">A panda is driving a car</td>
  <td width=25% style="text-align:center;">Monkey learning to play the piano</td>
  <td width=25% style="text-align:center;">A paper folding tiger is walking on table</td>
  <td width=25% style="text-align:center;">Unicorns running along a beach</td>
</tr> -->

<tr>
  <td style="text-align:center;"colspan="4"><b>With POS</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/2_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/3_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/4_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/9_wPOS.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">A panda is driving a car</td>
  <td width=25% style="text-align:center;">Monkey learning to play the piano</td>
  <td width=25% style="text-align:center;">A paper folding tiger is walking on table</td>
  <td width=25% style="text-align:center;">Unicorns running along a beach</td>
</tr>
</table>

### Real-World Videos(SCVideo)
<table class="center">
<tr>
  <td style="text-align:center;"colspan="4"><b>Without POS</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/6_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/131_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/15_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/16_woPOS.gif"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">A girl is laughing happily in front of the camera</td>
  <td width=25% style="text-align:center;">A boy is laughing happily in front of the camera</td>
  <td width=25% style="text-align:center;">Sea turtle swimming at the bottom of the ocean</td>
  <td width=25% style="text-align:center;">Clown fish swimming through the coral reef</td>
</tr> -->

<tr>
  <td style="text-align:center;"colspan="4"><b>With POS</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/6_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/13_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/151_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/16_wPOS.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">A girl is laughing happily in front of the camera</td>
  <td width=25% style="text-align:center;">A boy is laughing happily in front of the camera</td>
  <td width=25% style="text-align:center;">Sea turtle swimming at the bottom of the ocean</td>
  <td width=25% style="text-align:center;">Clown fish swimming through the coral reef</td>
</tr>
</table>

### UnReal-World Videos(SCVideo)
<table class="center">
<tr>
  <td style="text-align:center;"colspan="4"><b>Without POS</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/7_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/5_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/8_woPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/14_woPOS.gif"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">An astronaut is riding a horse in the space, in a photorealistic style</td>
  <td width=25% style="text-align:center;">A bear is dancing in the snow</td>
  <td width=25% style="text-align:center;">A panda is playing guitar in the bar</td>
  <td width=25% style="text-align:center;">A monkey is reading book in the library</td>
</tr> -->

<tr>
  <td style="text-align:center;"colspan="4"><b>With POS</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/71_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/5_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/8_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/141_wPOS.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">An astronaut is riding a horse in the space, in a photorealistic style</td>
  <td width=25% style="text-align:center;">A bear is dancing in the snow</td>
  <td width=25% style="text-align:center;">A panda is playing guitar in the bar</td>
  <td width=25% style="text-align:center;">A monkey is reading book in the library</td>
</tr>
</table>

## Video Diversity
### ModelScope with POS
<table class="center">

<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity0-0.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity0-1.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity0-2.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity0-3.gif"></td>
</tr>
<tr>
  <td style="text-align:center;"colspan="4"><b>Prompt:A paper folding tiger is walking on table</b></td>
</tr>
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/3_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity1-1.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity1-2.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity1-3.gif"></td>
</tr>
<tr>
  <td style="text-align:center;"colspan="4"><b>Prompt:Monkey learning to play the piano</b></td>
</tr>
</table>

### SCVideo with POS
<table class="center">

<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/13_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity2-1.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity2-2.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity2-3.gif"></td>
</tr>
<tr>
  <td style="text-align:center;"colspan="4"><b>Prompt:A boy is laughing happily in front of the camera</b></td>
</tr>

<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/141_wPOS.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity3-1.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity3-2.gif"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/diversity3-3.gif"></td>
</tr>
<tr>
  <td style="text-align:center;"colspan="4"><b>Prompt:A monkey is reading book in the library</b></td>
</tr>
</table>

## Image qualitative results
### SD-v1.5

<table class="center">
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img1_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img2_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img3_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img4_woPOS.jpg"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">A close-up of a knife and a cup on a surface</td>
  <td width=25% style="text-align:center;">A person is riding a dirt bike along a path</td>
  <td width=25% style="text-align:center;">A mirror shot of a dog sitting in a car</td>
  <td width=25% style="text-align:center;">A piece of dutch chocolate cake with a fork on a plate</td>
</tr> -->
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img1_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img2_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img3_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img4_wPOS.jpg"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">A close-up of a knife and a cup on a surface</td>
  <td width=25% style="text-align:center;">A person is riding a dirt bike along a path</td>
  <td width=25% style="text-align:center;">A mirror shot of a dog sitting in a car</td>
  <td width=25% style="text-align:center;">A piece of dutch chocolate cake with a fork on a plate</td>
</tr>

<tr>
  <td style="text-align:center;"colspan="4"><b> </b></td>
</tr>

<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img5_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img6_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img7_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img8_woPOS.jpg"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">A black and white cat laying in green vegetation</td>
  <td width=25% style="text-align:center;">A sculpture of a man reading a newspaper sitting at a bench</td>
  <td width=25% style="text-align:center;">A woman is sitting in front of a desk</td>
  <td width=25% style="text-align:center;">A person sitting on a bench with a view of a body of water</td>
</tr> -->
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img5_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img6_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img7_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img8_wPOS.jpg"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">A black and white cat laying in green vegetation</td>
  <td width=25% style="text-align:center;">A sculpture of a man reading a newspaper sitting at a bench</td>
  <td width=25% style="text-align:center;">A woman is sitting in front of a desk</td>
  <td width=25% style="text-align:center;">A person sitting on a bench with a view of a body of water</td>
</tr>
</table>

### SD-XL

<table class="center">
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img9_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img10_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img11_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img12_woPOS.jpg"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">A bird walking through a cafeteria next to a table</td>
  <td width=25% style="text-align:center;">A dog sitting in the front seat of a truck</td>
  <td width=25% style="text-align:center;">A man that is sitting at a desk with a pen and laptop</td>
  <td width=25% style="text-align:center;">An adult giraffe standing near a white duck in a field of grass</td>
</tr> -->
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img9_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img10_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img11_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img12_wPOS.jpg"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">A bird walking through a cafeteria next to a table</td>
  <td width=25% style="text-align:center;">A dog sitting in the front seat of a truck</td>
  <td width=25% style="text-align:center;">A man that is sitting at a desk with a pen and laptop</td>
  <td width=25% style="text-align:center;">An adult giraffe standing near a white duck in a field of grass</td>
</tr>

<tr>
  <td style="text-align:center;"colspan="4"><b> </b></td>
</tr>

<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img13_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img14_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img15_woPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img16_woPOS.jpg"></td>
</tr>
<!-- <tr>
  <td width=25% style="text-align:center;">Horses stand around on a neighborhood street in front of a car</td>
  <td width=25% style="text-align:center;">A man is on a bench in front of a steeple tower</td>
  <td width=25% style="text-align:center;">Two giraffes in a zoo enjoy a walk and a snack</td>
  <td width=25% style="text-align:center;">A man fixing a tire for a motorcycle</td>
</tr> -->
<tr>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img13_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img14_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img15_wPOS.jpg"></td>
  <td><img src="https://github.com/StevensXu/demo/blob/main/data/img16_wPOS.jpg"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">Horses stand around on a neighborhood street in front of a car</td>
  <td width=25% style="text-align:center;">A man is on a bench in front of a steeple tower</td>
  <td width=25% style="text-align:center;">Two giraffes in a zoo enjoy a walk and a snack</td>
  <td width=25% style="text-align:center;">A man fixing a tire for a motorcycle</td>
</tr>
</table>

