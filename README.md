# Proyecto-de-titulo
Estimación y monitoreo en tiempo real de la inercia en un sistema electrico


Este repositorio contiene el código y datos de mi proyecto de título en la Universidad de los Andes, enfocado en estimar la inercia de un sistema eléctrico a partir de mediciones locales de frecuencia y ROCOF.

El objetivo de este proyecto es desarrollar y comparar distintos modelos para estimar la inercia de un sistema eléctrico utilizando mediciones locales de frecuencia y ROCOF.
Se incluyen:

Métodos de referencia (SSA con fórmula ENTSO-E).

Modelos basados en redes neuronales profundas (CNN 1D y CNN-LSTM).

Dos enfoques de análisis temporal:

Secuencias largas (2s) → estimación continua.

Secuencias cortas (0.3s) → estimación rápida post-perturbación.

Referencia al paper base:
Poudyal, A., Fourney, R., Tonkoski, R., Hansen, T. M., Tamrakar, U., & Trevizan, R. D. (2020). Convolutional Neural Network-based Inertia Estimation using Local Frequency Measurements. In 2020 52nd North American Power Symposium (NAPS). IEEE. https://doi.org/10.1109/NAPS50074.2020.9336399 
