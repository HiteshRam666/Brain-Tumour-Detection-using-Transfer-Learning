# Brain🧠-Tumour-Detection-using-Transfer-Learning

A brain tumor is a collection, or mass, of abnormal cells in your brain. Your skull, which encloses your brain, is very rigid. Any growth inside such a restricted space can cause problems. Brain tumors can be cancerous (malignant) or noncancerous (benign). When benign or malignant tumors grow, they can cause the pressure inside your skull to increase. This can cause brain damage, and it can be life-threatening. Brain tumors are categorized as primary or secondary:

- A primary brain tumor originates in your brain. Many primary brain tumors are benign.
- A secondary brain tumor, also known as a metastatic brain tumor, occurs when cancer cells spread to your brain from another organ, such as lung or breast.

## **How is Brain Tumor diagnosed?**
![brain](https://github.com/HiteshRam666/Brain-Tumour-Detection-using-Transfer-Learning/assets/116026459/26f4d369-2737-48be-a55a-4ff64a39988e)

### **Magnetic Resonance Imaging (MRI)**
An MRI uses magnetic fields to produce detailed images of the body.
MRI can be used to measure the tumor’s size. A special dye called a contrast medium is given before the scan to create a clearer picture.
This dye can be injected into a patient’s vein or given as a pill or liquid to swallow.
MRIs create more detailed pictures than CT scans and are the preferred way to diagnose a brain tumor.
The MRI may be of the brain, spinal cord, or both, depending on the type of tumor suspected and the likelihood that it will spread in the CNS.
There are different types of MRI. The results of a neuro-examination, done by the internist or neurologist, helps determine which type of MRI to use.

## About Dataset 
[Link](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

## Transfer Learning: Resnet50

ResNet-50 is a convolutional neural network that is 50 layers deep. You can load a pretrained version of the neural network trained on more than a million images from the ImageNet database. The pretrained neural network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the neural network has learned rich feature representations for a wide range of images. The neural network has an image input size of 224-by-224.
![0_tH9evuOFqk8F41FG](https://github.com/HiteshRam666/Brain-Tumour-Detection-using-Transfer-Learning/assets/116026459/16dca2fc-1f65-4739-be01-a0705f6be7f2)

**Acheived the accuracy of 96% and val_accuracy of 80%**


