# ✨ Incantations

> *A collection of small spells, terminal charms, and bash sorcery to automate the mundane.*

Welcome to my personal grimoire. This repository houses the **Bash scripts** I use to bend the command line to my will.

## 🔮 The Spellbook

| Script | Effect |
| :--- | :--- |
| `apparate` | create links to the most common spells in the current folder |
| `status-all` | Check the status of all branches in all repositories |
| `pull-all` | Pull all branches in all repositories |
| `push-all` | Push all branches in all repositories |
| `update-code` | Commit/Push/Deploy changes of the same file in all repositories |

## 📜 How to Cast
To add these charms to your local environment, clone the repository and add the directory to your `$PATH`:

```bash
git clone [https://github.com/gildas/incantations.git](https://github.com/gildas/incantations.git)
./incantations/status-all -v
```

You can also apparate the most common spells in the current folder:

```bash
./incantations/apparate
# Then later....
./status-all -v
```
