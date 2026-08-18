---
layout: post
title: "Exploring Qwen Edit Model Capabilities in Boogu Edit"
date: 2026-08-18
categories: ai-testing
tags: [qwen, boogu, llm, testing]
---

In this initial post, we are testing the core features and capabilities of Qwen Edit using Boogu Edit. Refer to ![https://huggingface.co/Qwen/Qwen-Image-Edit-2511](https://huggingface.co/Qwen/Qwen-Image-Edit-2511)

# __Files__
boogu_image_edit_turbo_hotfix_1k_20260708_int8_convrot.safetensors

SHA256: b0bdd36eb559d62e8169e16a1e8b4438f8be17fc092ca9d43a2d8460c1d79e6a

## __Improve Character Consistency__
* [1. Test 1](#test-1)
* [2. Test 2](#test-2)
* [3. Test 3](#test-3)


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
![Test 1](https://github.sinimari.com/img/HDP_02.jpg)

### Input image:
![Test 1](https://github.sinimari.com/img/HDP_02_1.jpg)

### Prompt text:
```html
生成一张四宫格图片。以下要求：人物：参考图人物分四个画面呈现不同动作表情。左上：双手举过头顶比双“V”，眼睛大睁、嘴巴张开，露出惊讶活泼的神态。右上：双手托住脸颊，双眼微闭、嘴巴嘟起，脸颊带红晕，呈现可爱娇憨感。左下：头微侧，一只眼睛wink，舌头吐出，单手比“V”，俏皮搞笑。右下：双臂交叉在胸前，眉头微皱、嘴巴嘟起，呈现小傲娇神态。服饰：根据参考图不变。背景与风格：充满疯狂动物城等可爱卡通元素的彩色背景，整体为二次元动漫风格，画面色彩鲜艳、风格甜美治愈，每幅小图都有精致的卡通边框装饰，充满童趣感。
```
### Output image:
![Test 1](https://github.sinimari.com/img/HDP_02_2.jpg)

---

