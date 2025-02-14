Summary of changes from all Ploomber products. Used internally to create social media content. The entries are usually a subset of what we publish in each `CHANGELOG.md`.

## Ploomber - 0.22.4 (2023-06-01)

* [Feature] Add `executor` option to NotebookRunner to choose ploomber-engine or papermill. ploomber-engine provides enhanced capabilities for debugging, testing and monitoring notebook execution ([Documentation](https://docs.ploomber.io/en/latest/cookbook/nb_executors.html))
* [Fix] Fix error in `ScriptRunner` that didn't allow to import modules in script's directory ([#1072](https://github.com/ploomber/ploomber/issues/1072)) 

## JupySQL - 0.7.8 (2023-06-01)

* [Feature] Add `%sqlplot bar` and `%sqlplot pie` (#508) ([Example](https://jupysql.ploomber.io/en/latest/api/magic-plot.html#sqlplot-bar))

## JupySQL - 0.7.7 (2023-05-31)

* [Feature] `%sql --connections` now displays an HTML table in Jupyter and a text-based table in the terminal ([Example](https://jupysql.ploomber.io/en/latest/api/magic-sql.html#list-connections))
* [Doc] Hiding connection string when passing `--alias` when opening a connection ([#432](https://github.com/ploomber/jupysql/issues/432)) ([Example](https://jupysql.ploomber.io/en/latest/howto.html#hide-connection-string))
* [Doc] Added Howto documentation for enabling JupyterLab cell runtime display ([#448](https://github.com/ploomber/jupysql/issues/448)) ([Example](https://jupysql.ploomber.io/en/latest/howto/benchmarking-time.html))

