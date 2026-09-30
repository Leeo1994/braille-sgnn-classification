# Braille Classification with Spiking Graph Neural Networks

University of Bristol Master's thesis. A pipeline that classifies braille letters from tactile sensor data using a spiking graph neural network (SGNN).

## What it does
- Converts spatiotemporal tactile signals into graph structures with NetworkX
- Trains a custom SGNN on the graph data to classify braille letters
- Compares temporal binning windows (25-100 ms); the best setup, spike-count directed graphs, reached 46.7% accuracy

## Based on
Uses a modified version of the [TactiGraph]([https://github.com/AdvancedResearchInnovationCenter/TactiGraph]) algorithm.
