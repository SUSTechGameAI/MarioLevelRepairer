# A Novel CNet-assisted Evolutionary Level Repairer  

### paper

Shu, T., Wang, Z., Liu, J., & Yao, X. (2020). A Novel CNet-assisted Evolutionary Level Repairer and Its Applications to Super Mario Bros. *arXiv preprint arXiv:2005.06148*.

### Requirement

python3、pytorch、pygame

### How to use

##### CNet folder:

you can run data/generate.py to generate train and test data. "model.py" is for train and "test.py" if for test.

##### LevelGenerator folder:

1. you can run "GAN/generate_level.py" to get levels generated by GAN and  pick up some levels with defect.
2. you can run "RandomDestroyed/generate.py" to get random destroyed levels.

##### GA folder:

1. run "run.py" to reapir defective levels . And reuslts will be saved. (save figure will slow the speed.)
2. run "render.py" to visualize the repair process. "space" to stop playing. When you  stop playing, you can use "left arrow" and "right arrow" to control.
3. run "draw_graph.py" to draw the graph from repair results.
4. run "evaluate.py" to see how many true(wrong) tiles was changed to true(wrong) tiles after repair.
5. when you start a new repair, you can run "clear.py" to clear the old result.