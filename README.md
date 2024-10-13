# Infant Sleep Staging with Wearable Sensors and Deep Learning: Evaluating and Controlling Age-Related Effects
## Abstract
Sleep problems in early childhood have been linked to a wide range of health and
developmental problems. Sleep staging is used in clinical studies to diagnose problems
with sleep health. Standardized sleep staging requires a medical study of sleep, usually
polysomnography, including an electroencephalography (EEG) analysis by a medical
professional. For this reason, standard sleep staging is not a viable solution for
long-term studies of sleep at-home, and alternative methods are needed that allow
objective monitoring of sleep in the child’s natural sleep environment.
Ranta et al. (2021) have developed NApping PAnts (NAPPA), a wearable sensor for
infants that uses an accelerometer and a gyroscope to record abdominal movements
during sleep. We have developed a Bidirectional Gated Recurrent Unit -based
deep learning classifier for automatic sleep staging of infant sleep with the NAPPA
wearable using an annotated dataset of 36 recordings. The classifier achieved a
median accuracy of 77% in detecting stages of deep sleep, light sleep, and wake using
five movement activity and respiration related features derived from the sensor signal.
Infant sleep and its indicators, such as respiration rate, are dynamic and change
throughout the first two years after birth. This variability in sleep stage indicators
introduces potential challenges for deep learning-based classifiers, as the data used
to train them are usually composed of infants of varying ages.
In this thesis, we carry out a data analysis focusing on studying how the varying age
of infants impacts the features recorded by the NAPPA system, and subsequently
we attempt to find methods to refine the classifier’s performance in sleep staging,
addressing the dynamic nature of infant sleep patterns and the impact of age on
sleep behavior.
We found a distinct relationship between the age of infants and recorded features and
age and model performance. Our proposed methods, however, did not ultimately
offer any improvement in model performance. Despite the lack of improvement in
performance, our findings highlight the role of age in the context of sleep staging using
wearable sensors in infant populations. The relationship between age, sleep patterns,
and recorded features suggests that age-specific adjustments may be necessary to
enhance the accuracy of sleep stage classification models.
