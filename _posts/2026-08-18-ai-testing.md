---
layout: post
title: "Boogu Edit on Qwen Edit Demos 1"
date: 2026-08-18
categories: ai-testing
tags: [qwen, boogu, llm, testing]
---

In this initial post, we are evaluating Boogu Edit model against the test scenarios from the Qwen Edit demo. By applying Boogu Edit to nearly identical input images and editing prompts, we assess its relative output quality, instruction following ability and overall image output editing capabilities compared to Qwen Edit output. Refer to [https://huggingface.co/Qwen/Qwen-Image-Edit-2511](https://huggingface.co/Qwen/Qwen-Image-Edit-2511)

# __Files__
boogu_image_edit_turbo_hotfix_1k_20260708_int8_convrot.safetensors

SHA256: b0bdd36eb559d62e8169e16a1e8b4438f8be17fc092ca9d43a2d8460c1d79e6a

## __Improve Character Consistency__
* [1. Test 1](#test-1)
* [2. Test 2](#test-2)
* [3. Test 3](#test-3)
* [4. Test 4](#test-4)
* [5. Test 5](#test-5)
* [5. Test 6](#test-6)


## Test 1
![Test 1](https://github.sinimari.com/img/HDP_01.jpg)

### Input image:
![Test 1](https://github.sinimari.com/img/HDP_01_1.jpg)

### Prompt text:
```html
生成圣诞节主题，一位纯欲气质的美少女，图中人脸不变。松散的双麻花辫松散低扎（麻花辫上有布艺彩球装饰），少女气质，无辜眼神，头戴圣诞树造型发饰，小型锥形圣诞树整齐地固定在头顶，顶部是金色五角星，树身装饰着彩色灯串、金色铃铛、蝴蝶结、红蓝金小球，布置精致饱满；冷白皮，白嫩嫩的皮肤如琼玉般嫩滑，纯欲朦胧滤镜，红棕系眼影自然晕染，双手拿着圣诞老人玩具，圣诞氛围拉满，庆祝感眼神和表情，轻轻歪头，俏皮好看的动作，可爱与性感并存，反差；蓬松微乱发丝与头顶圣诞树自然融合；穿毛绒红色上衣，质感柔软蓬松；暖白背景、棚拍柔光、低对比度、低饱和度、细腻胶片颗粒、轻微色散光晕、胶片柔光感、温暖治愈氛围、独特视角，非常规构图，70mm胶片人像风格绿色涂鸦描边人物轮廓，描边周围空白处还有各种圣诞节元素的可爱涂鸦，充满童趣和圣诞氛围的手绘拼贴感。人物轮廓荧光红绿金色虚线波点包裹，写满了“MERRY CHRISMAS”可爱字体，中景
```
### Output image:
![Test 1](https://github.sinimari.com/img/HDP_01_2.jpg)

---

## Test 2
![Test 2](https://github.sinimari.com/img/HDP_02.jpg)

### Input image:
![Test 2](https://github.sinimari.com/img/HDP_02_1.jpg)

### Prompt text:
```html
生成一张四宫格图片。以下要求：人物：参考图人物分四个画面呈现不同动作表情。左上：双手举过头顶比双“V”，眼睛大睁、嘴巴张开，露出惊讶活泼的神态。右上：双手托住脸颊，双眼微闭、嘴巴嘟起，脸颊带红晕，呈现可爱娇憨感。左下：头微侧，一只眼睛wink，舌头吐出，单手比“V”，俏皮搞笑。右下：双臂交叉在胸前，眉头微皱、嘴巴嘟起，呈现小傲娇神态。服饰：根据参考图不变。背景与风格：充满疯狂动物城等可爱卡通元素的彩色背景，整体为二次元动漫风格，画面色彩鲜艳、风格甜美治愈，每幅小图都有精致的卡通边框装饰，充满童趣感。
```
### Output image:
![Test 2](https://github.sinimari.com/img/HDP_02_2.jpg)

---

## Test 3
![Test 3](https://github.sinimari.com/img/HDP_03.jpg)

### Input image:
![Test 3](https://github.sinimari.com/img/HDP_03_1.jpg)

### Prompt text:
```html
生成竖版3:4画面比例的“真人与其对应卡通壁画合影”场景图像：将上传的真实人物照片以原样保留服装、发型、妆容置于画面左侧/前方。在真人背后墙面绘制1:1对应卡通壁画，厚涂质感且采用动漫风格大眼、柔和轮廓五官，完整复刻发型、服装及配饰细节如耳环、项链等，色彩饱和度高并带有涂鸦式笔触效果。墙面添加彩色涂鸦爱心、笑脸、几何图案元素，地面点缀飞溅颜料装饰细节，壁画区域融入如“2026发财”的中文字元素，字体风格契合涂鸦美学。确保真人与壁画比例、角度自然衔接，光照方向统一符合场景逻辑，保持整体色彩风格一致，呈现生动、连贯且视觉和谐效果
```
### Output image:
![Test 3](https://github.sinimari.com/img/HDP_03_2.jpg)

---

## Test 4
![Test 4](https://github.sinimari.com/img/HDP_04.jpg)

### Input image:
![Test 4](https://github.sinimari.com/img/HDP_04_1.jpg)

### Prompt text:
```html
生成一个手拿着压制好的边缘不规则的平面像素拼豆成品照片，拼豆的内容是参考图中的像素Q版形象，拼豆扁平没有凸起，保持参考图主体特征不变，背景是工作台台面
```
### Boogu Prompt text:
```html
生成一个手拿着压制好的边缘不规则的平面像素拼豆成品照片，把图片变成16颜色平面像素Q版形象拼豆成品，拼豆扁平没有凸起，保持参考图主体特征不变，背景是工作台台面
```
### Output image:
![Test 4](https://github.sinimari.com/img/HDP_04_2.jpg)

---

## Test 5
![Test 5](https://github.sinimari.com/img/HDP_05.jpg)

### Input image:
![Test 5](https://github.sinimari.com/img/HDP_05_1.jpg)
![Test 5](https://github.sinimari.com/img/HDP_05_2.jpg)

### Prompt text:
```html
两个人，一起做一个“嘘”的手势。
```
### Boogu Prompt text:
```html
把图1男生和图2女生，放在一起，两个人，一起做一个“嘘”的手势。
```
### Output image:
![Test 5](https://github.sinimari.com/img/HDP_05_3.jpg)


### Boogu Prompt text:
```html
把图1女生和图2男生，放在一起，两个人，一起做一个“嘘”的手势。
```
### Output image:
![Test 5](https://github.sinimari.com/img/HDP_05_4.jpg)

---

## Test 6
![Test 6](https://github.sinimari.com/img/HDP_06.jpg)

### Input image:
![Test 6](https://github.sinimari.com/img/HDP_06_1.jpg)
![Test 6](https://github.sinimari.com/img/HDP_06_2.jpg)

### Prompt text:
```html
女生抱着这只小猫。
```
### Boogu Prompt text:
```html
图1的小猫被图2女生放在大腿上。图2女生举起双手抱着小猫。
```
### Output image:
![Test 6](https://github.sinimari.com/img/HDP_06_3.jpg)

---

