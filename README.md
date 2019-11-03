# Malaria-detection
I have used repository of segmented cells from the thin blood smear slide images from the Malaria Screener research activity and leveraged the power of Convolution Neural Networks (CNN) to detect whether a person is infected with malaria or not. In a ten-fold cross- validation based on 27,578 single cell images, the average accuracy of my 7-layer CNN model is 96.11%. The three transfer learning models I have used only achieves 95.48%(VGG16), 93.79%(ResNet50), 86.13%(Inception Network), respectively on the same images. The CNN model shows superiority over the transfer learning models in all performance indicators such as precision (0.96 vs 0.95 vs 0.94 vs0.86), F1 score (0.96 vs 0.95 vs 0.94 vs 0.86).


