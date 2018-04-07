# env_setting

## for tensorflow
1、put the cudnn in your own path

2、specify which gpu for running tensorflow

    CUDA_VISIBLE_DEVICES=0 python tf_demo.py
    CUDA_VISIBLE_DEVICES=1 sh ./run.sh

## for anaconda
not add to .bashrc when installing

export PATH=path2anaconda/bin:${PATH}

## for tmux
every time use shell, please use tmux first.

eg. tmux new -s sess_name_chen
