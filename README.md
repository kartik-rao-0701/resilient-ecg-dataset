# ECG Dataset

This repository contains the ECG datasets used in the research work **"Resilient ECG Monitoring System for Trojan Prevention."**

The dataset contains three types of ECG data:

* **user** – Original ECG data used as the input.
* **golden** – ECG data obtained from the trusted implementation without the hardware Trojan.
* **trojan** – ECG data obtained from the implementation with the hardware Trojan inserted.

The same ECG input is used for the golden and Trojan implementations so that their outputs can be compared.

## Folder Structure

```text
user/       User ECG data
golden/     Golden implementation data
trojan/     Trojan implementation data
```


