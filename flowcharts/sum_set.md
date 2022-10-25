# หาผลรวมของตัวเลขทั้งหมดในเซ็ตของเซ็ตที่มีจำนวนจริงอยู่ 10 ตัว จำนวน 10 เซ็ต

```mermaid
%% Sum all number in 10 sets (SETS) of 10 real numbers
flowchart TD
    s1([start]) --> sum[SUM=0]
    sum --> s2{done each SET in SETS}
    s2 -- false --> s3{done each NUMBER in SET}
    s3 -- false --> s4[SUM = SUM + NUMBER]
    s2 -- true --> print[print SUM]
    s3 -- true --> s2
    s4 --> s3
```

[![Sum all number in 10 sets (SETS) of 10 real numbers](https://mermaid.ink/img/pako:eNpdkctqwzAQRX9lEAQS6kDiZGVIFiVeuos6WVleqNa4NlhS0INSjP-9ku24TbUYNDPnztWjJ5XiSBKyWkHuBLCuA-nEB2poJex3YNAaWOfpNd-AqkNFI3swhmoq6059VQ3TFq6XkINfZr8ujPW1cgPb7RmME0V-y067ciG82diJe64kArKqAW8TbIPbsICx56BmncFJcPgjeLtlr-n7rPmVHP5JjsEcThDiyywqnw2sdhN81620xRgDXz4PXTATL43jfC4SEYFasJb79-xDkxLboEBKEr_lWDPXWUqoHDzq7pxZTHlrlSZJmBsR5qzKv2X1yCfm0rJPzQRJxhtFBEdNNv3b-H3DD81MjPQ?type=png)](https://mermaid.live/edit#pako:eNpdkctqwzAQRX9lEAQS6kDiZGVIFiVeuos6WVleqNa4NlhS0INSjP-9ku24TbUYNDPnztWjJ5XiSBKyWkHuBLCuA-nEB2poJex3YNAaWOfpNd-AqkNFI3swhmoq6059VQ3TFq6XkINfZr8ujPW1cgPb7RmME0V-y067ciG82diJe64kArKqAW8TbIPbsICx56BmncFJcPgjeLtlr-n7rPmVHP5JjsEcThDiyywqnw2sdhN81620xRgDXz4PXTATL43jfC4SEYFasJb79-xDkxLboEBKEr_lWDPXWUqoHDzq7pxZTHlrlSZJmBsR5qzKv2X1yCfm0rJPzQRJxhtFBEdNNv3b-H3DD81MjPQ)