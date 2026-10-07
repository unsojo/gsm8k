---
pretty_name: GSM8K — Grade School Math Word Problems
license: mit
language:
  - en
task_categories:
  - text2text-generation
source: https://github.com/openai/grade-school-math
features:
  question: string
  answer: string
---

# GSM8K: Grade School Math Word Problems

Math word problems at a grade-school level, each with a worked, step-by-step
solution. Problems take between 2 and 8 steps to solve using basic arithmetic
(adding, subtracting, multiplying, dividing). The final answer is written at the
end of each solution after `####`.

It's widely used to test whether AI models can reason through multi-step problems.

> **Copy for Project Clover.** This is a copy of the "main" version of GSM8K,
> shared here under its MIT license. All credit belongs to the original authors
> at OpenAI.

## Files

| File | Rows |
|------|-----:|
| `data/train.csv` | 7,473 |
| `data/test.csv` | 1,319 |

Columns:

- `question`: the word problem
- `answer`: the step-by-step solution, ending with `#### <final answer>`

## Original source

Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, and others, OpenAI (2021).
Code and data: https://github.com/openai/grade-school-math
Paper: https://arxiv.org/abs/2110.14168

## License

MIT License, as released by the original authors.

## Citation

```bibtex
@article{cobbe2021gsm8k,
  title   = {Training Verifiers to Solve Math Word Problems},
  author  = {Cobbe, Karl and Kosaraju, Vineet and Bavarian, Mohammad and others},
  journal = {arXiv preprint arXiv:2110.14168},
  year    = {2021}
}
```
