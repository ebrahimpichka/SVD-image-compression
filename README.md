# SVD-image-compression

Compressing RGB images using SVD matrix decomposition

## usage:

`K` is the number of important components selected after SVD decomposition

```
K = 50
compressed_image = compress_image(image_file_address, K=K)

plt.imshow(compressed_image)
plt.title(f'K = {K}')
plt.axis("off")
```

## results:

![dc1](https://github.com/ebrahimpichka/SVD-image-compression/blob/master/decomposed1.png)

![dc2](https://github.com/ebrahimpichka/SVD-image-compression/blob/master/decomposed2.png)

![dc3](https://github.com/ebrahimpichka/SVD-image-compression/blob/master/decomposed3.png)
