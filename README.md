# Lost-in-Conversation



## 📑 Resources

- We extend single harmful requests into multi-turn dialogue coreferences, covering ten languages (*English*, *Chinese*, *Italian*, *Vietnamese*, *Arabic*, *Korean*, *Thai*, *Bengali*, *Swahili*, and *Javanese*).

- We first generate an *English* dialogue context for each of the 400 harmful queries in [HarmBench](https://github.com/centerforaisafety/HarmBench) and use it as a seed dialogue coreference for multilingual conversation construction.

- We then extend each seed dialogue coreference into nine languages, maintaining a high translation quality as reported in our paper.



## ✏️ How to use

- You can use dialogue coreferences written entirely in a specific language for each query, or combine different languages to construct a single dialogue coreference to test model safety.



## 🙏🏻 Citation

If you find our resources useful in your research, please consider citing our paper:

```bibtex
To be updated
```



## ⚠️ Caution

The harmful queries are derived from existing safety benchmarks, and the preceding dialogues are constructed solely to provide multilingual context. Although our resources may be misused, we believe their value for multilingual safety evaluation and defense research outweighs this risk.
