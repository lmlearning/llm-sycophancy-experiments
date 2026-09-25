# LLM Sycophancy Evaluation and Training Experiments

Research scripts for investigating **sycophancy in language models**, including preference training, model inference and evaluation.

## Repository guide

| Area | Entry points |
| --- | --- |
| Preference training | [dpo_trainer.py](dpo_trainer.py), [train_7b.sh](train_7b.sh) |
| Model inference | [dpo_inference.py](dpo_inference.py) |
| Sycophancy evaluation | [sycophancy_eval_v4.py](sycophancy_eval_v4.py), [eval_7b.sh](eval_7b.sh) |
| Re-evaluation and processing | [reevalutate.py](reevalutate.py), [filter_keys.py](filter_keys.py) |
| Experiment material | [datasets](datasets/), [results](results/) |

## Reproducing experiments

Start with the shell scripts to see the model and dataset settings used for the experiments. Review the corresponding Python imports and configure local model, checkpoint and data paths before execution. Training and inference require an environment and hardware appropriate to the selected model.

The repository records research workflows and outputs. Interpret results together with their model, dataset and evaluation settings; the presence of a result file does not establish general model reliability.

## Related work

[SycBench](https://github.com/lmlearning/SycBench) provides a smaller, standard-library dataset transformation workflow for constructing sycophancy prompts.

[Research and publications](https://scholar.google.com/citations?user=Z86vj_MAAAAJ&hl=en)

## License

See [LICENSE](LICENSE).
