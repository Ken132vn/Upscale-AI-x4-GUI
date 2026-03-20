\# UpscaleLite-FP16



High-performance image upscaler optimized for low-to-mid end GPUs using ONNX Runtime and DirectML.



\## Features

\- \*\*Hardware Acceleration:\*\* Supports Nvidia, AMD, and Intel GPUs via DirectML.

\- \*\*VRAM Efficiency:\*\* Automated FP16 conversion to minimize memory footprint.

\- \*\*Stability:\*\* Dynamic tiling logic to prevent Out-of-Memory (OOM) errors.



\## Installation



1\. \*\*Install dependencies:\*\*

&nbsp;  ```bash

&nbsp;  pip install -r requirements.txt

&nbsp;  ```



2\. \*\*Prepare the Model:\*\*

&nbsp;  - Download the ONNX model (63.9 MB) from \[OpenModelDB](https://openmodeldb.info/models/4x-NomosWebPhoto-esrgan).

&nbsp;  - Rename the file to `4xNomosWebPhoto\_esrgan\_fp32\_opset17.onnx`.

&nbsp;  - Place it inside the `/models/` directory.



3\. \*\*Execute:\*\*

&nbsp;  ```bash

&nbsp;  python src/main.py

&nbsp;  ```



\## License \& Credits

\- \*\*Software:\*\* Licensed under the \*\*MIT License\*\*.

\- \*\*AI Model:\*\* \[4x-NomosWebPhoto-esrgan](https://openmodeldb.info/models/4x-NomosWebPhoto-esrgan) by \*\*luu\*\* (Licensed under \*\*CC-BY-4.0\*\*).

\- \*Note: This project does not distribute the model file. Users must download it from the official source.\*



\## Support the Project

If you find this tool helpful, consider supporting the developer:



\- \*\*MoMo:\*\* 0123 456 789 (Khang)

\- \*\*ZaloPay:\*\* 0123 456 789

\- \*\*MBBank:\*\* 0123456789 - NGUYEN TRUNG KHANG



---

\*The first execution will perform an automated FP16 conversion, which may take a few moments.\*

