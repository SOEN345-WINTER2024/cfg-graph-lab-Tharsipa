# Lab 7 
## Tharsipa Nadarajah - 40190597

### Basic Calculator onClick Method

- Step 1:  CFG Graph for onClick(): [Link to CFG](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-Tharsipa/blob/master/Lab7%20cfg/cfg_onClick.pdf)
- Step 2: Test requirements and test paths for Node Coverage

  TR: {1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23}
  
  Test paths: [1,3,23], [1,4,23], [1,5,23], [1,6,23], [1,7,23], [1,8,23],[1,9,23],[1,10,23],[1,11,23],[1,12,23],[1,13,23],[1,14,23],[1,15,23],[1,16,23],[1,2,23],[1,17,21,22,23],[1,17,18,22,23],[1,17,19,22,23],[1,17,20,22,23]

- Step 3: Test requirements and test paths for Edge Coverage

  TR: { (1,2), (1,3), (1,4), (1,5), (1,6), (1,7), (1,8), (1,9), (1,10), (1,11), (1,12), (1,13), (1,14), (1,15), (1,16), (1,17), (17,18), (17,19), (17,20), (17,21), (18,22), (19,22), (20,22), (21,22), (22,23), (2,23), (3,23), (4,23), (5,23), (6,23), (7,23), (8,23), (9,23), (10,23), (11,23), (12,23), (13,23), (14,23), (15,23), (16,23) }
  
  Test paths: [1,3,23], [1,4,23], [1,5,23], [1,6,23], [1,7,23], [1,8,23], [1,9,23], [1,10,23], [1,11,23], [1,12,23], [1,13,23], [1,14,23], [1,15,23], [1,16,23], [1,2,23], [1,17,21,22,23], [1,17,18,22,23], [1,17,19,22,23], [1,17,20,22,23]

- Step 4: Test requirements and test paths for Edge Pair Coverage
  
  TR: { (1,2,23), (1,3,23), (1,4,23), (1,5,23), (1,6,23), (1,7,23), (1,8,23), (1,9,23), (1,10,23), (1,11,23), (1,12,23), (1,13,23), (1,14,23), (1,15,23), (1,16,23), (1,17,18), (1,17,19), (1,17,20), (1,17,21), (17,18,22), (17,19,22), (17,20,22), (17,21,22), (18,22,23), (19,22,23), (20,22,23), (21,22,23)}

  
  Test paths: [1,2,23], [1,3,23], [1,4,23], [1,5,23], [1,6,23], [1,7,23], [1,8,23], [1,9,23], [1,10,23], [1,11,23], [1,12,23], [1,13,23], [1,14,23], [1,15,23], [1,16,23], [1,17,18,22,23], [1,17,19,22,23], [1,17,20,22,23], [1,17,21,22,23]

### CycleStreets app doPauseResume method

- Step 1:  CFG Graph for doPauseResume(): [Link to CFG](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-Tharsipa/blob/master/Lab7%20cfg/CycleStreets_doPauseResume_cfg.pdf)
- Step 2: Test requirements and test paths for Node Coverage

  TR: {1,2,3,4,5}
  
  Test paths: [1,2,3,5],[1,2,4,5]
  
- Step 3: Test requirements and test paths for Edge Coverage

  TR: {(1,2),(2,3),(2,4),(3,5),(4,5)}

  Test paths: [1,2,3,5],[1,2,4,5]

- Step 4: Test requirements and test paths for Edge Pair Coverage

  TR: {(1,2,3),(1,2,4),(2,3,5),(2,4,5)}

  Test paths: [1,2,3,5],[1,2,4,5]
  
