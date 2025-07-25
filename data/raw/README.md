# Raw data
Sylvain Schmitt -
Jul 25, 2025

This folder will contains the raw data for all analyses. In particular:

- `dry_weight.xlsx` the leaf dry weights
- `hydrated/` the leaf hydrated measurements
- `leaves/` the sampling field sheets
- `osmo/` the leaf hydrated measurements with osmometer
- `plantation/` the inventories and GIS data of the plantation
- `sample_taken.xlsx` the list of sampled individuals for leaf or wood
- `scans/` the leaf hydrated scans
- `teamplates/` template files for data acquisition

``` r
fs::dir_tree()
```

    .
    ├── README.md
    ├── README.qmd
    ├── README.rmarkdown
    ├── dry_weight.xlsx
    ├── hydrated
    │   ├── HYD_20250708.xls
    │   ├── HYD_20250709.xls
    │   ├── HYD_20250710.xls
    │   ├── HYD_20250711.xls
    │   ├── HYD_20250712.xls
    │   └── HYD_template.xls
    ├── leaves
    │   ├── 20250707_A.pdf
    │   ├── 20250707_B.pdf
    │   ├── 20250708.pdf
    │   ├── 20250709.pdf
    │   ├── 20250710_leaf.pdf
    │   ├── 20250710_wood.pdf
    │   ├── 20250711_leaf.pdf
    │   └── 20250711_wood.pdf
    ├── osmo
    │   ├── FEF25_TLP-10072025.xlsx
    │   ├── FEF25_TLP-11072025.xlsx
    │   ├── FEF25_TLP-12072025.xlsx
    │   ├── TLP_20250708.xlsx
    │   └── TLP_20250709.xlsx
    ├── plantation
    │   ├── BosquePesquisaEmbrapa.gpkg
    │   └── Dados brutos do inventário da estrada 5.xlsx
    ├── sample_taken.xlsx
    ├── scans
    │   ├── SCAN08072025
    │   │   ├── ANGEL_5663_1.pdf
    │   │   ├── ANGEL_5663_2.pdf
    │   │   ├── ANGEL_5663_3.pdf
    │   │   ├── ANGEL_5663_4.pdf
    │   │   ├── ANGEL_5663_5.pdf
    │   │   ├── ANGEL_5677_1.pdf
    │   │   ├── ANGEL_5677_2.pdf
    │   │   ├── ANGEL_5677_3.pdf
    │   │   ├── ANGEL_5677_4.pdf
    │   │   ├── ANGEL_5677_5.pdf
    │   │   ├── ANGEL_5993_1.pdf
    │   │   ├── ANGEL_5993_2.pdf
    │   │   ├── ANGEL_5993_3.pdf
    │   │   ├── ANGEL_5993_4.pdf
    │   │   ├── ANGEL_5993_5.pdf
    │   │   ├── CASTA_5744_1.pdf
    │   │   ├── CASTA_5744_2.pdf
    │   │   ├── CASTA_5744_3.pdf
    │   │   ├── CASTA_5744_4.pdf
    │   │   ├── CASTA_5744_5.pdf
    │   │   ├── FAVAO_5685_1.pdf
    │   │   ├── FAVAO_5685_2.pdf
    │   │   ├── FAVAO_5685_3.pdf
    │   │   ├── FAVAO_5685_4.pdf
    │   │   ├── FAVAO_5685_5.pdf
    │   │   ├── FAVA_5455_1.pdf
    │   │   ├── FAVA_6513_1.pdf
    │   │   ├── FAVA_6513_2.pdf
    │   │   ├── FAVA_6513_3.pdf
    │   │   ├── FAVA_6513_4.pdf
    │   │   ├── FAVA_6513_5.pdf
    │   │   ├── PEQUI_5950_1.pdf
    │   │   ├── PEQUI_5950_2.pdf
    │   │   ├── PEQUI_5950_3.pdf
    │   │   ├── PEQUI_5950_4.pdf
    │   │   ├── PEQUI_5950_5.pdf
    │   │   ├── PEQUI_5953_1.pdf
    │   │   ├── PEQUI_5953_2.pdf
    │   │   ├── PEQUI_5953_3.pdf
    │   │   ├── PEQUI_5953_4.pdf
    │   │   └── PEQUI_5953_5.pdf
    │   ├── SCAN09072025
    │   │   ├── ANGEL_6243_1.pdf
    │   │   ├── ANGEL_6243_2.pdf
    │   │   ├── ANGEL_6243_3.pdf
    │   │   ├── ANGEL_6243_4.pdf
    │   │   ├── ANGEL_6243_5.pdf
    │   │   ├── ANGEL_6528_1.pdf
    │   │   ├── ANGEL_6528_2.pdf
    │   │   ├── ANGEL_6528_3.pdf
    │   │   ├── ANGEL_6528_4.pdf
    │   │   ├── ANGEL_6528_5.pdf
    │   │   ├── CASTA_6568_1.pdf
    │   │   ├── CASTA_6568_2.pdf
    │   │   ├── CASTA_6568_3.pdf
    │   │   ├── CASTA_6568_4.pdf
    │   │   ├── CASTA_6568_5.pdf
    │   │   ├── CASTA_6617_1.pdf
    │   │   ├── CASTA_6617_2.pdf
    │   │   ├── CASTA_6617_3.pdf
    │   │   ├── CASTA_6617_4.pdf
    │   │   ├── CASTA_6617_5.pdf
    │   │   ├── FREIJ_6564_1.pdf
    │   │   ├── FREIJ_6564_2.pdf
    │   │   ├── FREIJ_6564_3.pdf
    │   │   ├── FREIJ_6564_4.pdf
    │   │   ├── FREIJ_6564_5.pdf
    │   │   ├── JARAN_6248_1.pdf
    │   │   ├── JARAN_6248_2.pdf
    │   │   ├── JARAN_6248_3.pdf
    │   │   ├── JARAN_6248_4.pdf
    │   │   ├── JARAN_6248_5.pdf
    │   │   ├── JARAN_6515_1.pdf
    │   │   ├── JARAN_6515_2.pdf
    │   │   ├── JARAN_6515_3.pdf
    │   │   ├── JARAN_6515_4.pdf
    │   │   ├── JARAN_6515_5.pdf
    │   │   ├── JARAN_6517_1.pdf
    │   │   ├── JARAN_6517_2.pdf
    │   │   ├── JARAN_6517_3.pdf
    │   │   ├── JARAN_6517_4.pdf
    │   │   ├── JARAN_6517_5.pdf
    │   │   ├── JUTAI_5961_1.pdf
    │   │   ├── JUTAI_5961_2.pdf
    │   │   ├── JUTAI_5961_3.pdf
    │   │   ├── JUTAI_5961_4.pdf
    │   │   ├── JUTAI_5961_5.pdf
    │   │   ├── PIQUI_5968_1.pdf
    │   │   ├── PIQUI_5968_2.pdf
    │   │   ├── PIQUI_5968_3.pdf
    │   │   ├── PIQUI_5968_4.pdf
    │   │   ├── PIQUI_5968_5.pdf
    │   │   ├── PIQUI_5971_1.pdf
    │   │   ├── PIQUI_5971_2.pdf
    │   │   ├── PIQUI_5971_3.pdf
    │   │   ├── PIQUI_5971_4.pdf
    │   │   ├── PIQUI_5971_5.pdf
    │   │   ├── PIQUI_6510_1.pdf
    │   │   ├── PIQUI_6510_2.pdf
    │   │   ├── PIQUI_6510_3.pdf
    │   │   ├── PIQUI_6510_4.pdf
    │   │   ├── PIQUI_6510_5.pdf
    │   │   ├── VIROL_6631_1.pdf
    │   │   ├── VIROL_6631_2.pdf
    │   │   ├── VIROL_6631_3.pdf
    │   │   ├── VIROL_6631_4.pdf
    │   │   ├── VIROL_6631_5.pdf
    │   │   ├── VIROL_6632_1.pdf
    │   │   ├── VIROL_6632_2.pdf
    │   │   ├── VIROL_6632_3.pdf
    │   │   ├── VIROL_6632_4.pdf
    │   │   ├── VIROL_6632_5.pdf
    │   │   ├── VIROL_6636_1.pdf
    │   │   ├── VIROL_6636_2.pdf
    │   │   ├── VIROL_6636_3.pdf
    │   │   ├── VIROL_6636_4.pdf
    │   │   └── VIROL_6636_5.pdf
    │   ├── SCAN10072025
    │   │   ├── COPAI_6894_1.pdf
    │   │   ├── COPAI_6894_2.pdf
    │   │   ├── COPAI_6894_3.pdf
    │   │   ├── COPAI_6894_4.pdf
    │   │   ├── COPAI_6896_1.pdf
    │   │   ├── COPAI_6897_1.pdf
    │   │   ├── COPAI_6897_2.pdf
    │   │   ├── COPAI_6897_3.pdf
    │   │   ├── COPAI_6897_4.pdf
    │   │   ├── COPAI_6897_5.pdf
    │   │   ├── COPAI_6898_1.pdf
    │   │   ├── COPAI_6898_2.pdf
    │   │   ├── COPAI_6898_3.pdf
    │   │   ├── COPAI_6898_4.pdf
    │   │   ├── COPAI_6898_5.pdf
    │   │   ├── COPAI_6910_1.pdf
    │   │   ├── COPAI_6910_2.pdf
    │   │   ├── FREIJ_7121_1.pdf
    │   │   ├── FREIJ_7121_2.pdf
    │   │   ├── FREIJ_7121_3.pdf
    │   │   ├── FREIJ_7121_4.pdf
    │   │   ├── FREIJ_7121_5.pdf
    │   │   ├── FREIJ_7134_1.pdf
    │   │   ├── FREIJ_7134_2.pdf
    │   │   ├── FREIJ_7134_3.pdf
    │   │   ├── FREIJ_7134_4.pdf
    │   │   ├── FREIJ_7134_5.pdf
    │   │   ├── QUARU_7333_1.pdf
    │   │   ├── QUARU_7333_2.pdf
    │   │   ├── QUARU_7333_3.pdf
    │   │   ├── QUARU_7333_4.pdf
    │   │   ├── QUARU_7333_5.pdf
    │   │   ├── QUARU_7334_1.pdf
    │   │   ├── QUARU_7334_2.pdf
    │   │   ├── QUARU_7334_3.pdf
    │   │   ├── QUARU_7334_4.pdf
    │   │   ├── QUARU_7334_5.pdf
    │   │   ├── QUARU_7589_1.pdf
    │   │   ├── QUARU_7589_2.pdf
    │   │   ├── QUARU_7589_3.pdf
    │   │   ├── QUARU_7589_4.pdf
    │   │   ├── QUARU_7589_5.pdf
    │   │   ├── VIROL_6404_1.pdf
    │   │   ├── VIROL_6404_2.pdf
    │   │   ├── VIROL_6404_3.pdf
    │   │   ├── VIROL_6404_4.pdf
    │   │   ├── VIROL_6637_1.pdf
    │   │   ├── VIROL_6637_2.pdf
    │   │   ├── VIROL_6637_3.pdf
    │   │   ├── VIROL_6637_4.pdf
    │   │   └── VIROL_6637_5.pdf
    │   ├── SCAN11072025
    │   │   ├── ANDIR_266_1.pdf
    │   │   ├── ANDIR_266_2.pdf
    │   │   ├── ANDIR_266_3.pdf
    │   │   ├── ANDIR_266_4.pdf
    │   │   ├── ANDIR_266_5.pdf
    │   │   ├── ANDIR_270_1.pdf
    │   │   ├── ANDIR_270_2.pdf
    │   │   ├── ANDIR_270_3.pdf
    │   │   ├── ANDIR_270_4.pdf
    │   │   ├── ANDIR_270_5.pdf
    │   │   ├── ANDIR_656_1.pdf
    │   │   ├── ANDIR_656_2.pdf
    │   │   ├── ANDIR_656_3.pdf
    │   │   ├── ANDIR_656_4.pdf
    │   │   ├── ANDIR_656_5.pdf
    │   │   ├── ANDIR_661_1.pdf
    │   │   ├── ANDIR_661_2.pdf
    │   │   ├── ANDIR_661_3.pdf
    │   │   ├── ANDIR_661_4.pdf
    │   │   ├── ANDIR_661_5.pdf
    │   │   ├── ANDIR_820_1.pdf
    │   │   ├── ANDIR_820_2.pdf
    │   │   ├── ANDIR_820_3.pdf
    │   │   ├── ANDIR_820_4.pdf
    │   │   ├── ANDIR_820_5.pdf
    │   │   ├── CEDRU_123_1.pdf
    │   │   ├── CEDRU_123_2.pdf
    │   │   ├── CEDRU_123_3.pdf
    │   │   ├── CEDRU_123_4.pdf
    │   │   ├── CEDRU_123_5.pdf
    │   │   ├── CEDRU_1623_1.pdf
    │   │   ├── CEDRU_1623_2.pdf
    │   │   ├── CEDRU_1623_3.pdf
    │   │   ├── CEDRU_1623_4.pdf
    │   │   ├── CEDRU_1623_5.pdf
    │   │   ├── CEDRU_278_1.pdf
    │   │   ├── CEDRU_278_2.pdf
    │   │   ├── CEDRU_278_3.pdf
    │   │   ├── CEDRU_278_4.pdf
    │   │   ├── CEDRU_278_5.pdf
    │   │   ├── CEDRU_292_1.pdf
    │   │   ├── CEDRU_292_2.pdf
    │   │   ├── CEDRU_292_3.pdf
    │   │   ├── CEDRU_292_4.pdf
    │   │   ├── CEDRU_292_5.pdf
    │   │   ├── CEDRU_527_1.pdf
    │   │   ├── CEDRU_527_2.pdf
    │   │   ├── CEDRU_527_3.pdf
    │   │   ├── CEDRU_527_4.pdf
    │   │   ├── CEDRU_527_5.pdf
    │   │   ├── JARAN_6947_1.pdf
    │   │   ├── JARAN_6947_2.pdf
    │   │   ├── JARAN_6947_3.pdf
    │   │   ├── JARAN_6947_4.pdf
    │   │   ├── JARAN_6947_5.pdf
    │   │   ├── PARAP_1391_1.pdf
    │   │   ├── PARAP_1391_2.pdf
    │   │   ├── PARAP_1391_3.pdf
    │   │   ├── PARAP_1391_4.pdf
    │   │   ├── PARAP_2035_1.pdf
    │   │   ├── PARAP_2035_2.pdf
    │   │   ├── PARAP_2035_3.pdf
    │   │   ├── PARAP_2035_4.pdf
    │   │   ├── PARAP_2035_5.pdf
    │   │   ├── PARAP_276_1.pdf
    │   │   ├── PARAP_276_2.pdf
    │   │   ├── PARAP_5375_1.pdf
    │   │   ├── PARAP_5375_2.pdf
    │   │   ├── PARAP_5375_3.pdf
    │   │   ├── PARAP_5375_4.pdf
    │   │   ├── PARAP_5375_5.pdf
    │   │   ├── PARAP_5887_1.pdf
    │   │   ├── PARAP_5887_2.pdf
    │   │   ├── PARAP_5887_3.pdf
    │   │   ├── PARAP_5887_4.pdf
    │   │   └── PARAP_5887_5.pdf
    │   └── SCAN12072025
    │       ├── COPAI_6910_1.pdf
    │       ├── COPAI_6910_2.pdf
    │       ├── COPAI_6910_3.pdf
    │       ├── COPAI_6910_4.pdf
    │       ├── COPAI_6910_5.pdf
    │       ├── CUPIU_8116_1.pdf
    │       ├── CUPIU_8116_2.pdf
    │       ├── CUPIU_8116_3.pdf
    │       ├── CUPIU_8116_4.pdf
    │       ├── CUPIU_8116_5.pdf
    │       ├── CUPIU_8188_1.pdf
    │       ├── CUPIU_8188_2.pdf
    │       ├── CUPIU_8188_3.pdf
    │       ├── CUPIU_8188_4.pdf
    │       ├── CUPIU_8188_5.pdf
    │       ├── CUPIU_8383_1.pdf
    │       ├── CUPIU_8383_2.pdf
    │       ├── CUPIU_8383_3.pdf
    │       ├── CUPIU_8383_4.pdf
    │       ├── CUPIU_8383_5.pdf
    │       ├── CUPIU_8452_1.pdf
    │       ├── CUPIU_8452_2.pdf
    │       ├── CUPIU_8452_3.pdf
    │       ├── CUPIU_8452_4.pdf
    │       ├── CUPIU_8452_5.pdf
    │       ├── CUPIU_9103_1.pdf
    │       ├── CUPIU_9103_2.pdf
    │       ├── CUPIU_9103_3.pdf
    │       ├── CUPIU_9103_4.pdf
    │       ├── CUPIU_9103_5.pdf
    │       ├── FREIJ_6416_1.pdf
    │       ├── FREIJ_6416_2.pdf
    │       ├── FREIJ_6416_3.pdf
    │       ├── FREIJ_6416_4.pdf
    │       ├── FREIJ_6416_5.pdf
    │       ├── JARAN_4646_1.pdf
    │       ├── JARAN_4646_2.pdf
    │       ├── JARAN_4646_3.pdf
    │       ├── JARAN_4646_4.pdf
    │       ├── JARAN_4646_5.pdf
    │       ├── QUARU_7541_1.pdf
    │       ├── QUARU_7541_2.pdf
    │       ├── QUARU_7541_3.pdf
    │       ├── QUARU_7541_4.pdf
    │       ├── QUARU_7541_5.pdf
    │       ├── QUARU_8499_1.pdf
    │       ├── QUARU_8499_2.pdf
    │       ├── QUARU_8499_3.pdf
    │       ├── QUARU_8499_4.pdf
    │       └── QUARU_8499_5.pdf
    ├── table.tsv
    └── templates
        ├── TLP_template.xlsx
        ├── template_HYD.ods
        └── template_TLP.ods
