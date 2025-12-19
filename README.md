# GOT
## Repository for the Generalized Overconfidence Task (GOT)
All resources pertaining the GOT!

Try the GOT here: https://cornell.ca1.qualtrics.com/jfe/form/SV_e2l3jyOPHwjinu6

### Description
There are 3 folders containing various resources related to implementing the GOT in your own research. These folders include:

1) `qualtrics` has all files related to importing the GOT into Qualtrics.
    `GOT.qsf` allows you to directly import the GOT into your Qualtrics account. Additional code for the Qualtrics to ensure the GOT runs smoothly are also included. 

    Qualtrics Javacsript files:
    The `GOT_image_preload.rtf` preloads the images to eliminate load-time delays and should be added to the Javascript portion for the `GOT_Inst` question, while `GOT_page_advance.rtf` autoadvances each GOT image after 250 ms and should be added to the `GOT_image` question. The `GOT_conf_slider.rtf` should be applied to the `GOT_conf` and the `GOT_q_hide.rtf` should be applied to `GOT_ID`, `GOT_Answer`, and `loop_number`.

2) `data_analysis` provides some basic code to analysis the GOT in r.
    The `example_project` folder contains example data and a basic script that can be used to clean the data and calculate mean values at a subject level. See the `README.md` in this folder for additional details.

3) `example_usages` includes publications using the GOT. If you would like to add you work to the list please email me with the publication and suggested citation.

### Suggested citation when using the GOT
Binnendyk, J., & Pennycook, G. (2024). Individual differences in overconfidence: A new measurement approach. Judgment and Decision Making, 19, e28. doi:10.1017/jdm.2024.22

### Contact
email: **jdbinnendyk@gmail.com**

If there is anything else you would like to see added to this repository let me know!