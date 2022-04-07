<h3>This folder contains the code used for merging datasets.
<br>Following files can be found here:
</h3>
<ul>
  <li><i>VDem_VParty_WB_basic_indicators_code.ipynb</i> - in this file I merged following datasets:
    <br>V-Party (https://github.com/MateuszMarcol/PopulismDatasets/blob/main/datasets_raw/V-Dem-CPD-Party-V2.csv),
    <br>V-Dem (https://www.v-dem.net/vdemds.html)
    <br>WB basic indicators (https://github.com/MateuszMarcol/PopulismDatasets/blob/main/datasets_raw/WB_basic_indicators.csv
    <br>VParty contains observations for a given party in a given year and I treat it as a "base" dataset. I add a country-year-specific VDem and WB data to each party observation; therefore, all parties from the same country in the same year have the same data assigned. I do not drop any variables from any sets while merging.
    <br><br><b>Disclaimers</b>:
    <br>- multiple variables in VParty and VDem have the same labels, throught the merging process they have obtained a suffix - "_x" for VParty and "_y" for VDem
  </li>
</ul>

