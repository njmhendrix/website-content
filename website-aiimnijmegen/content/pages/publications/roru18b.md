title: Pectoral muscle segmentation in breast tomosynthesis with deep learning
authors: A. Rodriguez-Ruiz, J. Teuwen, K. Chung, N. Karssemeijer, M. Chevalier, A. Gubern-Merida and I. Sechopoulos
has_pdf: True
template: publication
bibkey: roru18b
published_in: Medical Imaging
pub_details: in: <i>Medical Imaging</i>, 2018
doi: https://doi.org/10.1117/12.2292920
Digital breast tomosynthesis (DBT) has superior detection performance than mammography (DM) for population-based breast cancer screening, but the higher number of images that must be reviewed poses a challenge for its implementation. This may be ameliorated by creating a twodimensional synthetic mammographic image (SM) from the DBT volume, containing the most relevant information. When creating a SM, it is of utmost importance to have an accurate lesion localization detection algorithm, while segmenting fibroglandular tissue could also be beneficial. These tasks encounter an extra challenge when working with images in the medio-lateral oblique view, due to the presence of the pectoral muscle, which has similar radiographic density. In this work, we present an automatic pectoral muscle segmentation model based on a u-net deep learning architecture, trained with 136 DBT images acquired with a single system (different BIRADS ® densities and pathological findings). The model was tested on 36 DBT images from that same system resulting in a dice similarity coefficient (DSC) of 0.977 (0.967-0.984). In addition, the model was tested on 125 images from two different systems and three different modalities (DBT, SM, DM), obtaining DSCs between 0.947 and 0.970, a range determined visually to provide adequate segmentations. For reference, a resident radiologist independently annotated a mix of 25 cases obtaining a DSC of 0.971. The results suggest the possibility of using this model for inter-manufacturer DBT, DM and SM tasks that benefit from the segmentation of the pectoral muscle, such as SM generation, computer aided detection systems, or patient dosimetry algorithms.
