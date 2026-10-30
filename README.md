# factory-config

Program for a Factory install: agent definitions and pipeline rules.

The Factory image is the engine. This repo is what it runs. Product work happens in product repositories. Secrets stay in the Factory secret store.

After a product PR merges, the monitor agent may open a learn PR here. Merge that PR to change the next work item. In-flight items keep the config SHA they started with.
