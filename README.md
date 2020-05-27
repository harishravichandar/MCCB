# Skill Acquisition via Multi-Coordinate Cost Balancing (MCCB)

## Abstract
We propose a learning framework, named Multi-Coordinate Cost Balancing (MCCB), to address the problem of acquiring point-to-point movement skills from demonstrations. MCCB encodes demonstrations simultaneously in multiple differential coordinates that specify local geometric properties. MCCB generates reproductions by solving a convex optimization problem with a multi-coordinate cost function and linear constraints on the reproductions, such as initial, target, and via points. Further, since the relative importance of each coordinate system in the cost function might be unknown for a given skill, MCCB learns optimal weighting factors that balance the cost function. We demonstrate the effectiveness of MCCB via detailed experiments conducted on one handwriting dataset and three complex skill datasets.

## Experiments
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/ISBZC9uRp5A/0.jpg)](http://www.youtube.com/watch?v=ISBZC9uRp5A)

## Paper
Read more about MCCB in our [ICRA-2019 paper](https://arxiv.org/pdf/1903.11725.pdf).

## Reference

H. Ravichandar<sup>#</sup>, S.R. Ahmadzadeh<sup>#</sup>, M. A. Rana, S. Chernova. "Skill acquisition via automated multi-coordinate cost balancing", *IEEE International Conference on Robotics and Automation (ICRA)*, 2019, pp. 7776-7782.
(<sup>#</sup>contributed equally)

```
@INPROCEEDINGS{ravichandar2019skill,
    TITLE={Skill Acquisition via Automated Multi-Coordinate Cost Balancing},
    AUTHOR={Ravichandar, Harish and Ahmadzadeh, S. Reza and Rana, M. Asif and Chernova, Sonia},
    BOOKTITLE={{IEEE} International Conference on Robotics and Automation ({ICRA})},
    PAGES={7776--7782},
    YEAR={2019},
    MONTH={May},
    ADDRESS={Montreal, Canada},
    %DOI={10.1109/ICRA.2015.7139728}
}
```
