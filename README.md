# DQM-HcalTasks

Following the CMS DQM-DC Run3 compaign of ML4DQM, HCAL creates Spatio-Temporal Anomaly Detection with Graph Deep Model for HB/HE channel monitoring (https://indico.cern.ch/event/1155250/contributions/4853721/attachments/2434393/4169212/DESMOD_AD_Spatio_Tempo_HEOnlineDQM_HCAL_DPG.pdf), with ONNX integration into CMSSW.

The AD models utilize digioccupancy maps of the HE and HB of the HCAL to detect spatio-temporal channel anomalies.

The inference with ONNX Runtime follows examples here: https://cms-ml.github.io/documentation/inference/onnx.html


