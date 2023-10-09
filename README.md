<div align="center"> 

<h1>✨QuadDet✨</h1> 

𝘼 𝙎𝙝𝙖𝙥𝙚-𝙗𝙖𝙨𝙚𝙙 𝙌𝙪𝙖𝙙𝙧𝙖𝙣𝙜𝙡𝙚 𝙛𝙤𝙧 𝘼𝙚𝙧𝙞𝙖𝙡 𝙄𝙢𝙖𝙜𝙚𝙨

</div>

## Introduction

This is the official implementation of QuadDet, which is implemented on [OBBDetection](https://github.com/jbwang1997/OBBDetection)


## Installation

Please refer to [install.md](docs/install.md) for installation and dataset preparation.

## Get Started

### How to use OBBDetection

If you want to train or test a oriented model, please refer to [oriented_model_starting.md](docs/oriented_model_starting.md).

### How to Start QuadDet

To help you start quickly, I prepare a simple bash script

#### Train


```bash
config=/path/to/config && work_dir=/path/to/work_dir && cuda=(device_id, like 0, 1, 2, 3 ...)
bash my_exps/train.sh ${config} ${work_dir} ${cuda}
```

#### Test

```bash
config=/path/to/config && ckpt=/path/to/checkpoint && save_dir=/path/to/results_save_dir && cuda=(same as above)
bash my_exps/test.sh ${config} ${ckpt} ${save_dir} ${cuda}
```

### How to Deploy QuadDet

## License

This project is released under the [Apache 2.0 license](LICENSE).
