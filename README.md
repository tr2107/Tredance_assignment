# Tredance_assignment
redence — Mini Workflow Engine (AI Engineer Intern Assignment)

## Overview

This repository contains a minimal workflow/agent engine implemented in Python using FastAPI.

It supports:

- Defining a graph of nodes (node_name -> function)

- Passing state between nodes

- Edges for sequencing (next node)

- Loop/stop flag logic

- Tool registry (function lookup)

- FastAPI endpoints to create graphs, run them, and view logs

This submission implements **Option A — Code Review Mini-Agent**:

Nodes implemented:

- extract\_functions — count functions

- check\_complexity — estimate LOC + rough complexity

- detect\_issues — find TODO, print, pass

- suggest\_improvements — increase quality_score until threshold
