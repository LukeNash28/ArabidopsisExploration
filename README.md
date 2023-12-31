# Arabidopsis Data Exploration and Multivariate Analysis

This project illustrates exploratory data analysis and the use of descriptive and diagnostic statistics concerning the growth of three ecotypes of Thale-cress *Arabidopsis thaliana*. Some techniques employed include MANOVA, Hotelling's T<sup>2</sup> test and multivariate tests of normality.

### Background Information

Regrettably, owing to legal obligations surrounding copyright, the data can not be made available publicly. The data was collected as part of a lab practical at Durham University in December 2022, and the HTML file is adapted from the code written for an assessment relating to that practical.

*Arabidopsis thaliana* is a plant which has a broad distribution in the Northern Hemisphere whose extensive use use in plant biology and genomics have lead to it being heralded as a "model organism" within these fields. This scientific intrigue has been inflated by the fact that numerous ecotypes have been documented with a wide range of characteristics relating to a vast array of aspects of its life history (Beck, et al., 2008). For instance, disparities in tolerance for saline environments between several of its ecotypes have been documented, likely due to differential expression of sodium transporter genes (Jha, et al., 2010), and investigations of salinity tolerance in plants is a priority in lieu of increased global interest in food security. Investigations such as this one are especially valuable where genetic screening procedures are unfeasible, scant or absent.

### Data Collection Protocol
Roughly 15 seeds of Columbia-0 (Col-0), Shakdara (Sha) and Zurich-0 (Zu-0) *Arabidopsis thaliana* ecotypes were sown onto plates made up with one of two treatments: one with 1.2% agar and Murashige and Skoog (MS) growth culture medium, and another with the above treatment with 50mM NaCl added. The plates were placed in a growth cabinet on a 16 hour lighting cycle for 3 days at 4<sup>0</sup>C, followed by an additional 21 days at 20<sup>0</sup>C. The plants on each plate were then extracted from the growth medium. The number of leaves and lateral roots on each plant were counted, and the diameter of the rosette and the length of the root from the centre of the rosette to its longest tip were measured under a microscope by straightening the plant out and counting the number of squares of 1mm x 1mm graph paper spanned by either the root or rosette respectively. Plants that failed to grow and others which were damaged during the extraction process to the extent that data could not be collated were discounted from the data set.

### Discussion
Research performed using transcriptomic and physiological analyses suggests that the Sha ecotype is able to better withstand abiotic stress compared to other ecotypes, including Col (Wang, et al., 2013), so the fact that the Sha ecotype showed no significant physiological changes in our protocol is notable. However, in Wang et al. (2013), the concentration of salt which yielded physiological differences was double that used in this protocol. This suggests that the local adaptation observed in the Sha ecotype is only apparent in highly saline environments. An expansion of this study which would incorporate these observations would be to grow plants of each ecotype at a higher number of different salt concentrations.

Sodium salts are also not the sole class of salts that may induce salinity stress for plants. Genetic screening done by Sun et al. (2015) showed K+ transporter genes were upregulated significantly in tolerant ecotypes even when exposed to NaCl salinity up to 200 mM concentration, and the same study showed that Na+ transporter genes showed no discernible change in transcriptional output. This suggests that Na+ exposure does not necessarily lead to universal changes at the transcriptional level which in turn suggests that physiological changes may not necessarily be evident even if there is a genetic predisposition for tolerance to salt. A way to negate any effects as a result of any differential responses to different mineral ions would be to grow the ecotypes under exposure to different salts, especially K+, since it is entirely plausible that an ecotype’s tolerance to salt could encompass multiple ions or ones that are different to the one we used in the protocol. This conjecture consequently negates this study’s ability to characterise the exact trends in salt tolerance among said ecotypes.

#### Bibliography
Beck, J., Schmuths, H. & Schaal, B., 2008. Native range genetic variation in Arabidopsis thaliana is strongly geographically structured and reflects Pleistocene glacial dynamics. *Molecular Ecology*, 17(3), pp. 902-915.

Jha, D., Shirley, N., Tester, M. & Roy, S., 2010. Variation in salinity tolerance and shoot sodium accumulation in Arabidopsis ecotypes linked to differences in the natural expression levels of transporters involved in sodium transport. *Plant, Cell & Environment*, 33(5), pp. 793-804.

Sun, Y. et al., 2015. Potassium Retention under Salt Stress Is Associated with Natural Variation in Salinity Tolerance among Arabidopsis Accessions. *PLoS One*, 10(5), p. e0124032.

Wang, Y. et al., 2013. Transcriptomic and Physiological Variations of Three Arabidopsis Ecotypes in Response to Salt Stress. *PLoS One*, 8(7), p. e69036.



