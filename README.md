# <u> :flying_saucer: Image Captioning </u>
<ul>
  <li> It is the process of generating a textual description for given images. </li>
  <li> It has been a very important and fundamental task in the Deep Learning domain. Image captioning has a huge amount of application. </li>
  <li> Image captioning can be regarded as an end-to-end Sequence to Sequence problem, as it converts images, which is regarded as a sequence of pixels to a sequence of words. </li>
</ul>

- [ ] Now, how about the idea work?

![image](https://user-images.githubusercontent.com/92979885/203905645-458d4281-ed0b-4499-880d-329389397065.png)

<p> If we are told to describe it, maybe we will describe it as: “A puppy on a blue towel” or “A brown dog playing with a green ball”. 
So, how are we doing this? </p> 
<p> While forming the description, we are seeing the image but at the same time, we are looking to create a meaningful sequence of words. </p>
<ol>
  <li> The first part is handled by CNNs. </li>
  <li> The second is handled by RNNs. </li>
 </ol>

## <u> :hourglass_flowing_sand: Modules Used </u>
- [x] TensorFlow
```bash
pip install tensorflow -cpu
```
- [x] Numpy
```bash
pip install numpy
```
- [x] Matplotlib
```bash
pip install matplotlib
```

## <u> :paintbrush: System Architecture </u>
<p> There are two basic types of architecture: </p>

![image](https://user-images.githubusercontent.com/92979885/203908470-f073a315-237f-4e87-94e2-25ce783fc09b.png)

The first architecture is called ```Injecting Architecture``` & the second one is called ```Merging Architecture```
<ul>
  <li> In the Injecting Architecture, the image data is introduced along with the language data, and the image and language data mixture are represented together.</li>
  <li> In the Merging Architecture, the image data is not introduced in the RNN network. So, the image and the language information are encoded separately.</li>
</ul>

## <u> :open_file_folder: Dataset Description </u>

> A surfer is surfing on a wave.

![image](https://user-images.githubusercontent.com/92979885/203908889-4edfa687-7e08-410a-9b23-a970d0ac474c.png)

## <u> :dart: Results </u>

![image](https://user-images.githubusercontent.com/92979885/203909290-4ee1c202-99d5-4468-8bf8-387132b1b0b9.png)
