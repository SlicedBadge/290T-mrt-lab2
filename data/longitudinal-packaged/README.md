# longitudinal brainwave dataset

This dataaset contains one person performing a series of tasks based on [a video stimulus](https://www.youtube.com/watch?v=sxqlOoBBjvc) every day for 58 days.

## details

These time-domain data were collected using a Mindwave, a single-electrode device with a sampling rate of 512, using the [NeuroView](https://store.neurosky.com/products/mindset-research-tools) application.
 
Each file contains around 10 to 12 minutes worth of data. The subject continued recording for another ~5 minutes after the end of the color counting task. We label all data after the color tasks as "unlabeled."

[This stimulus video](https://www.youtube.com/watch?v=sxqlOoBBjvc&feature=youtu.be) were used for every day. The color RED were used for the color counting task, and at the end of the color task, the subject blinked five times, and then continued with general computing tasks for another five minutes, such as reading on the computer screen and typing on the keyboard.

## data format

Data in `labeled/*.csv` are indexed by the day on which they were collected. Each reading is strictly ordered time-domain reading, with times relative to the stimulus beginning, and with each reading labled by the stimulus displayed at that time.
