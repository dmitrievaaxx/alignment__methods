**Запуск:**  
- organization-aikrivoshein  - `python -m datasphere.main project job execute -p bt1ige70pc08t7r0o6of -c sft_main_config.yaml`  
  
**Как работаь с wandb:**
- Скачать папку output.tar.gz с DataSphereJobs и достать файлик .wandb
- Зайти в Google Colab (APY=c72a4e8a4377fdd45b974054e1dd6a3e3ef13744)
```py
!pip install wandb -q
!wandb sync <название файла>.wandb
```
