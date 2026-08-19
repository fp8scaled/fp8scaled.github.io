---
layout: post
title: "Boogu Edit on Qwen Edit Demos 2"
date: 2026-08-19
categories: ai-testing
tags: [qwen, boogu, llm, testing]
---

Continue evaluating Boogu Edit model against the test scenarios from the Qwen Edit demo. By applying Boogu Edit to nearly identical input images and editing prompts, we assess its relative output quality, instruction following ability and overall image output editing capabilities compared to Qwen Edit output. Refer to [https://huggingface.co/Qwen/Qwen-Image-Edit-2511](https://huggingface.co/Qwen/Qwen-Image-Edit-2511)

# __Files__
boogu_image_edit_turbo_hotfix_1k_20260708_int8_convrot.safetensors

SHA256: b0bdd36eb559d62e8169e16a1e8b4438f8be17fc092ca9d43a2d8460c1d79e6a

## __Lora Integration - Relighting__
* [1. Test 7](#test-7)
* [2. Test 8](#test-8)
## __Lora Integration - Novel View Synthesis__
* [3. Test 9](#test-9)
* [4. Test 10](#test-10)
## __Industry Design__
* [5. Test 11](#test-11)
* [5. Test 12](#test-12)
* [5. Test 13](#test-13)
* [5. Test 14](#test-14)


## Test 7
![Test 7](https://github.sinimari.com/img/HDP_07.jpg)

### Input image:
![Test 7](https://github.sinimari.com/img/HDP_07_1.jpg)

### Prompt text:
```html
柔光,使用柔和光线对图片进行重新照明
```
### Output image:
![Test 7](https://github.sinimari.com/img/HDP_07_2.jpg)

---

## Test 8
![Test 8](https://github.sinimari.com/img/HDP_08.jpg)

### Input image:
![Test 8](https://github.sinimari.com/img/HDP_08_1.jpg)

### Prompt text:
```html
柔光,使用柔和光线对图片进行重新照明
```
### Boogu Prompt text:
```html
对图片进行重新照明
```
### Output image:
![Test 8](https://github.sinimari.com/img/HDP_08_2.jpg)

---

## Test 9
![Test 9](https://github.sinimari.com/img/HDP_09.jpg)

### Input image:
![Test 9](https://github.sinimari.com/img/HDP_09_1.jpg)

### Prompt text:
```html
将镜头平移至桌面特写
```
### Boogu Prompt text:
```html
把镜头移到桌面上的树枝造型四头烛台进行放大特写
```
### Output image:
![Test 9](https://github.sinimari.com/img/HDP_09_2.jpg)

---

---

