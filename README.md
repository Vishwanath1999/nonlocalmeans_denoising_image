# nonlocalmeans_denoising_image
Image denoising using non-local means method

Non-local means is an algorithm in image processing for image denoising. Unlike "local mean" filters, which take the mean value of a group of pixels surrounding a target pixel to smooth the image, non-local means filtering takes a mean of all pixels in the image, weighted by how similar these pixels are to the target pixel. This results in much greater post-filtering clarity, and less loss of detail in the image compared with local mean algorithms.

If compared with other well-known denoising techniques, non-local means adds "method noise" (i.e. error in the denoising process) which looks more like white noise, which is desirable because it is typically less disturbing in the denoised product. Recently non-local means has been extended to other image processing applications such as deinterlacing, view interpolation, and depth maps regularization.

If the input image is a colour image break it into 3 coor channels and supply them one by one as input. After denoising the components can be merged to get back the colour image.
