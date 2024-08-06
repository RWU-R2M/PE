---
title: "Primary Energy Storage v1.0.0"
---
%% v1.0.0

graph LR

subgraph Primary-Battery
Cells[[6S LiPo Cell Array]] --> |10mm<sup>2</sup> \n | BMS{{Primary BMS}} --> F1([Primary Fuse])
end

Cells -.-> BConn>test]
F1 & Cells--> PConn[/test\]
