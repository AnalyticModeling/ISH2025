# Abstract for ISH2025

## Conference
[International Symposium of Hearing 2025](https://easychair.org/smart-program/ISH2025/2025-06-05.html#talk:277104)

## Title
Direct Characteristics-Based Design of Filterbanks for Perceptual Studies and Speech and Hearing Technologies

## Author
Samiya A Alkhairy

## Keywords
* Auditory filter design
* Filterbank design
* Frequency-domain characteristics
* Perceptual studies


## Abstract
We develop methods for auditory filterbanks design that directly use specified frequency-domain filter characteristics such as peak frequencies, various bandwidths, and group delays [^1]. This ability to directly design filters based on specified characteristics enables (1) accurate design of auditory filters, and (2) systematic studies of the dependence of findings of perceptual studies on filter characteristics. In contrast, existing filter design methods generally do not allow for design based on filter characteristics, erroneously design higher-order auditory filters based on formulas for quality factors of second order filters, or offer limited control over filter characteristics. 

We design auditory filters by direct specification of any two frequency-domain characteristics alongside peak frequency and peak magnitude – e.g. n-dB quality factors, ERB, and group delay. We derive closed-form parameterizations of the transfer functions in terms of sets of filter characteristics which ensures direct control over behavior and enables systematic variation. The methods are accurate, direct, simple, stable, computationally efficient, avoid iterative processes, and are appropriate for various species. To our knowledge, no existing methods exhibit this degree of accuracy, simplicity, and control.

Our approach enables specification of various sets of characteristics depending on the needs of a particular study. For instance, it enables simultaneous specification of mixed magnitude- and phase-based characteristics (e.g., ERB and group delay), allowing for sharply tuned responses without excessive group delay and for control over both frequency selectivity and synchronization in filterbanks. It also enables control over the shape of the frequency response magnitude – e.g. through simultaneous specification of 3dB and 15dB quality factors.

The characteristics-based methods for direct design of auditory filter addresses two critical needs: accurately designing auditory filters based on simultaneous specifications on characteristics, and systematically studying how varying characteristics affects the findings of perceptual studies and technological advances. For instance, the methods (using our open-source code [^2]) may be used to systematically investigate the dependence of study outcomes on filter characteristics in studies reporting sensitivity based on ad hoc variation of certain characteristics. These include intelligibility scores of bandpass-filtered speech [^3], accuracy of speech recognition [^4], sound source localization models [^5], mutual information between articulatory gestures of vocal tracts and acoustic and perceptual features [^6], and accuracy of speech intelligibility models for cochlear implants [^7]. The methods may be extended to incorporate specifications on combined spectrotemporal characteristics as is relevant for studying certain perceptual functions [^8]. This work may also be used to understand the cochlea's role in perception via underlying unified models [^9].


## References
[^1]: Alkhairy, S. A. (2024). Characteristics-Based Design of Generalized-Exponent Bandpass Filters. arXiv preprint [arXiv:2404.15321](https://arxiv.org/abs/2404.15321).
[^2]: Zhao, W., & Alkhairy, S. A. (2025) [GEFs GitHub Repository](https://github.com/AnalyticModeling/GEFs).
[^3]: Warren, R. M., Bashford Jr, J. A., & Lenz, P. W. (2004). Intelligibility of bandpass filtered speech: Steepness of slopes required to eliminate transition band contributions. The Journal of the Acoustical Society of America, 115(3), [1292-1295.](https://pubs.aip.org/asa/jasa/article-abstract/115/3/1292/546754/Intelligibility-of-bandpass-filtered-speech)
[^4]: Dimitriadis, D., Maragos, P., & Potamianos, A. (2010). On the effects of filterbank design and energy computation on robust speech recognition. IEEE transactions on audio, speech, and language processing, 19(6), [1504-1516.](https://ieeexplore.ieee.org/abstract/document/5638124) *and* Slaney, M., & Seltzer, M. L. (2014). The influence of pitch and noise on the discriminability of filterbank features. In INTERSPEECH (Vol. 14, pp. [2263-2267](https://www.isca-archive.org/interspeech_2014/slaney14_interspeech.pdf)).
[^5]: Dietz, M., Ewert, S. D., & Hohmann, V. (2011). Auditory model based direction estimation of concurrent speakers from binaural signals. Speech Communication, 53(5), [592-605.](https://www.sciencedirect.com/science/article/pii/S016763931000097X)
[^6]: Ghosh, P. K., Goldstein, L. M., & Narayanan, S. S. (2011). Processing speech signal using auditory-like filterbank provides least uncertainty about articulatory gestures. The Journal of the Acoustical Society of America, 129(6), [4014-4022.](https://pmc.ncbi.nlm.nih.gov/articles/PMC3135153/)
[^7]: Cosentino, S., Falk, T. H., McAlpine, D., & Marquardt, T. (2013). Cochlear implant filterbank design and optimization: A simulation study. IEEE/ACM Transactions on Audio, Speech, and Language Processing, 22(2), [347-353.](https://ieeexplore.ieee.org/abstract/document/6661369)
[^8]: Moore, B. C. (2008). The role of temporal fine structure processing in pitch perception, masking, and speech perception for normal-hearing and hearing-impaired people. Journal of the Association for Research in Otolaryngology, 9, [399-406.](https://link.springer.com/article/10.1007/s10162-008-0143-x)
[^9]: Alkhairy, S. A., & Shera, C. A. (2019). An analytic physically motivated model of the mammalian cochlea. The Journal of the Acoustical Society of America, 145(1), [45-60.](https://pmc.ncbi.nlm.nih.gov/articles/PMC6320697/) *and* Alkhairy, S. A. (2024). Cochlear wave propagation and dynamics in the human base and apex: Model-based estimates from noninvasive measurements. In AIP Conference Proceedings (Vol. 3062, No. 1). [AIP Publishing.](https://arxiv.org/abs/2407.00003)
