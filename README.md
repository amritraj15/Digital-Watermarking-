# Digital-Watermarking-
<p>
This Project deals with implementation of Image Watermarking which provides mechanism in hiding the watermark in an image file (host image) without much distortion of the image quality. An evolutionary algorithm, Cuckoo Search (CS) algorithm, is applied in finding the optimal scaling factors (SFs) to improve robustness and imperceptibility.
</p>
<p>
The Watermarked image is then subjected to many attacks to find the robustness of the watermark image. Then, on calculating Peak-Signal-to-Noise-Ratio (PSNR) and Normalized Correlation (NC), the suitable watermark image for the host image is taken out. Further, it is applied on the video by converting the video into a number of frames and apply one level discrete cosine or discrete wavelet transform on randomly selected frames. Then, whenever there is a scene change detected, the corresponding frame is taken and the coefficients of the low and high frequency sub bands are modified by embedding the watermark multiplied by SFs. In CS, for Lévy flight, which represents variation of random walk, McCulloch’s algorithm and Mantegna Algorithm is used. Several attacks are done on the watermarked frame to check for its robustness. After the attacks are completed, the video is reconstructed from the frames.
</p>

Supervisor : Assistant Professor <b>Mihir Sing </b> (	Department of Computer Science & Engineering, MAKAUT,WB (WBUT)).
Working Environment : Matlab
