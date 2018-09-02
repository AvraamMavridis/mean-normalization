# mean-normalization

[![npm version](https://badge.fury.io/js/mean-normalization.svg)](https://badge.fury.io/js/mean-normalization) [![Greenkeeper badge](https://badges.greenkeeper.io/AvraamMavridis/rescaling-value.svg)](https://greenkeeper.io/) [![Build Status](https://travis-ci.org/AvraamMavridis/mean-normalization.svg?branch=master)](https://travis-ci.org/AvraamMavridis/mean-normalization)

<img src="https://github.com/AvraamMavridis/mean-normalization/blob/master/mean_normalization.png?raw=true" />

where x is an original value, x' is the normalized value.

```
import meanNormalize from 'meanNormalize';

meanNormalize(5, [1,2,3,4,5]); // 0.5
meanNormalize(1, [1,2,3,4,5]); // -0.5
```
