## SANER 2018: How Scientists Develop Scientific Software

This repository contains the main files used in the repositories analysis section of the paper "How Scientists Develop Scientific Software". If you want to reproduce our data, please read on the steps.

### * Steps
1. Clone our repository using: ```git clone https://github.com/fronchetti/SANER-2017```. <br>
2. To reproduce the data collection process: ```python data_collector.py```. This script will create folders and files related to all the projects inside <i>responses.csv</i>, and you may need to allow it on your system. The collected data will be available in the <i>Dataset</i> folder.<br>

  If you want to jump this step, just use our compacted version of the <i>Dataset</i> folder:
  https://github.com/fronchetti/SANER-2018/tree/master/Dataset

3. The <i>summary.csv</i> file contains general information about the projects. If you want to recreated this file use: ```python data_information.py```. <b> Step required to generate boxplots</b>.

4. The <i>quarters.csv</i> file contains commits frequency in all projects, grouped by quarters. If you want to recreated this file use: ```python data_timeseries.py```. <b> Step required to generate time series</b>.

5. If you want to generate our charts, use <i>summary.R</i>. Ready versions of <i>summary.csv</i> and <i>quarters.csv</i> are available in this repository.

### * Contact
Troubles? Feel free to get in touch: <br>
Luiz Felipe Fronchetti - fronchettiemail@gmail.com
