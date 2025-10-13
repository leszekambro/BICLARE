# BICLARE

This page presents additional companion material for ...

---

## Six Virtual Environments  FIG. 5 

<p align="center">
  <img src="experiments/maps/house_map.png" width="30%" />
  <img src="experiments/maps/house_tilted_map.png" width="30%" />
  <img src="experiments/maps/office_map.png" width="30%" />
</p>

<p align="center">
  <img src="experiments/maps/office_tilted_map.png" width="30%" />
  <img src="experiments/maps/museum_map.png" width="30%" />
  <img src="experiments/maps/museum_tilted_map.png" width="30%" />
</p>

<p align="center"><em>Figure 5: Six virtual maps used for performance evaluation of the BICLARE algorithm.</em></p>

## Six Virtual Environments  FIG. 6
<h2>Localization Error Heatmaps</h2>

<h3>Magnitude heatmaps (<i>M<sub>mag</sub></i>)</h3>

<table style="width:100%; text-align:center;">
  <tr>
    <th>House</th>
    <th>Office</th>
    <th>Museum</th>
  </tr>
  <tr>
    <td><img src="experiments/heatmaps/error_heatmap_house.png" width="250"></td>
     <td><img src="experiments/heatmaps/error_heatmap_office.png" width="250"></td>
    <td><img src="experiments/heatmaps/error_heatmap_museum.png" width="250"></td>
  </tr>
</table>

<p><b>Figure 1.</b> Localization error magnitude heatmaps <i>M<sub>mag</sub></i>. 
For all maps: μ = 0.226, min = 0.004, max = 1.033, σ = 0.152, median = 0.193.</p>

<hr>

<h3>Direction heatmaps (<i>M<sub>dir</sub></i>)</h3>

<table style="width:100%; text-align:center;">
  <tr>
    <th>House</th>
    <th>Office</th>
    <th>Museum</th>
  </tr>
  <tr>
    <td><img src="experiments/heatmaps/error_direction_heatmap_house.png" width="250"></td>
    <td><img src="experiments/heatmaps/error_direction_heatmap_office.png" width="250"></td>
    <td><img src="experiments/heatmaps/error_direction_heatmap_museum.png" width="250"></td>
  </tr>
</table>

<p><b>Figure 2.</b> Localization error direction heatmaps <i>M<sub>dir</sub></i>.</p>

<h3>Orientation Error Heatmaps <i>M<sub>θ</sub></i></h3>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">

  <div style="text-align: center;">
    <img src="experiments/heatmaps/error_orientation_heatmap_house.png" width="300" alt="House heatmap">
    <p><b>House</b></p>
  </div>

  <div style="text-align: center;">
    <img src="experiments/heatmaps/error_orientation_heatmap_office.png" width="300" alt="Office heatmap">
    <p><b>Office</b></p>
  </div>

  <div style="text-align: center;">
    <img src="experiments/heatmaps/error_orientation_heatmap_museum.png" width="300" alt="Museum heatmap">
    <p><b>Museum</b></p>
  </div>

</div>

<p><b>Figure:</b> Orientation error heatmaps <i>M<sub>θ</sub></i> for different environments.</p>


<h3>Dynamic Obstacles and Agent Deployment</h3>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">

  <div style="text-align: center;">
    <img src="experiments/arenas_spawn_boxes/house_arena_with_spawn_boxes.png" width="280" alt="House arena">
    <p><b>House</b></p>
  </div>

  <div style="text-align: center;">
    <img src="experiments/arenas_spawn_boxes/office_arena_with_spawn_boxes.png" width="280" alt="Office arena">
    <p><b>Office</b></p>
  </div>

  <div style="text-align: center;">
    <img src="experiments/arenas_spawn_boxes/museum_arena_with_spawn_boxes.png" width="280" alt="Museum arena">
    <p><b>Museum</b></p>
  </div>

</div>

<p><b>Figure:</b> Dynamic obstacles with spawn order (red) and agent deployment positions (blue) in each map.</p>

<h3>Examples of Generated Maps (for <i>f<sub>e</sub> = 1.5</i>)</h3>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">

  <div style="text-align: center; width: 30%;">
    <img src="results/map_plots/quadtree_map_relayed_pipuck2_house_tilted_n_1.5_tspawn_0_2_agents_s5.csv.png" 
         alt="House tilted map" style="width:100%; border:1px solid #ccc; border-radius:6px;">
    <p><b>House_tilted</b><br>
    <i>N<sub>A</sub>=2</i>, <i>T<sub>spawn</sub>=0</i><br>
    F<sub>1</sub>=87.2%, CP<sub>m</sub>=78.9%</p>
  </div>

  <div style="text-align: center; width: 30%;">
    <img src="results/map_plots/quadtree_map_relayed_pipuck4_office_tilted_n_1.5_st_180_6_agents_s1.csv.png" 
         alt="Office map" style="width:100%; border:1px solid #ccc; border-radius:6px;">
    <p><b>Office</b><br>
    <i>N<sub>A</sub>=6</i>, <i>T<sub>spawn</sub>=180</i><br>
    F<sub>1</sub>=88.8%, CP<sub>m</sub>=91.9%</p>
  </div>

  <div style="text-align: center; width: 30%;">
    <img src="results/map_plots/quadtree_map_relayed_pipuck1_museum_tilted_n_1.5_st_100_s1_15_agents.csv.png" 
         alt="Museum tilted map" style="width:100%; border:1px solid #ccc; border-radius:6px;">
    <p><b>Museum_tilted</b><br>
    <i>N<sub>A</sub>=15</i>, <i>T<sub>spawn</sub>=100</i><br>
    F<sub>1</sub>=89.6%, CP<sub>m</sub>=99.8%</p>
  </div>

</div>

<p><b>Figure:</b> Examples of generated maps from experiments with <i>f<sub>e</sub> = 1.5</i>.</p>

<h3>Performance of different algorithms across all maps and swarm sizes (for <i>f<sub>e</sub> = 0</i>)</h3>



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Performance Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff;
      margin: 30px;
      line-height: 1.4;
    }

    h1 {
      text-align: center;
      margin-bottom: 20px;
    }

    .table-container {
      max-height: 650px;
      overflow: auto;
      border: 1px solid #ccc;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }

    table {
      border-collapse: collapse;
      width: 100%;
      min-width: 1100px;
      font-size: 12px;
    }

    caption {
      caption-side: top;
      font-weight: bold;
      margin-bottom: 8px;
      font-size: 14px;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 5px 6px;
      text-align: center;
      white-space: nowrap;
    }

    th {
      background-color: #f2f2f2;
      position: sticky;
      top: 0;
      z-index: 2;
    }

    tr:nth-child(even) td {
      background-color: #fafafa;
    }

    i {
      font-style: italic;
    }

    .bold {
      font-weight: bold;
    }
  </style>
</head>
<body>

<h1>Performance of Different Algorithms</h1>

<div class="table-container">
<table>
  <caption>Performance across all maps and swarm sizes (f<sub>e</sub> = 0)</caption>
  <tr>
    <th>Map</th>
    <th>N<sub>A</sub></th>
    <th>ACP BICLARE-PP</th>
    <th>ACP BICLARE-WF</th>
    <th>ACP FSP-QT</th>
    <th>ACP FSP-G</th>
    <th>ACP FSP</th>
    <th>AAC BICLARE-PP</th>
    <th>AAC BICLARE-WF</th>
    <th>AAC FSP-QT</th>
  </tr>

  <!-- house -->
  <tr><td><i>house</i></td><td>2</td><td class="bold">69.40</td><td>66.68</td><td>49.12</td><td>61.19</td><td>61.68</td><td class="bold">0.2023</td><td>0.2001</td><td>0.1543</td></tr>
  <tr><td><i>house</i></td><td>4</td><td class="bold">82.74</td><td>78.30</td><td>68.23</td><td>70.00</td><td>69.33</td><td class="bold">0.2450</td><td>0.2259</td><td>0.1849</td></tr>
  <tr><td><i>house</i></td><td>6</td><td class="bold">84.78</td><td>84.41</td><td>75.09</td><td>75.77</td><td>77.05</td><td class="bold">0.2733</td><td>0.2420</td><td>0.1977</td></tr>
  <tr><td><i>house</i></td><td>10</td><td>84.65</td><td>85.67</td><td>80.47</td><td>84.49</td><td class="bold">86.71</td><td class="bold">0.3053</td><td>0.2769</td><td>0.2551</td></tr>
  <tr><td><i>house</i></td><td>15</td><td class="bold">88.73</td><td>87.77</td><td>84.56</td><td>85.44</td><td>87.47</td><td class="bold">0.3203</td><td>0.2896</td><td>0.2812</td></tr>

  <!-- house_tilted -->
  <tr><td><i>house_tilted</i></td><td>2</td><td>61.01</td><td class="bold">69.86</td><td>43.69</td><td>56.87</td><td>63.91</td><td class="bold">0.2145</td><td>0.2002</td><td>0.1979</td></tr>
  <tr><td><i>house_tilted</i></td><td>4</td><td>75.80</td><td class="bold">79.37</td><td>56.19</td><td>71.58</td><td>72.29</td><td class="bold">0.2470</td><td>0.2342</td><td>0.2191</td></tr>
  <tr><td><i>house_tilted</i></td><td>6</td><td>80.11</td><td>81.25</td><td>63.43</td><td>64.11</td><td class="bold">75.41</td><td class="bold">0.2730</td><td>0.2550</td><td>0.2423</td></tr>
  <tr><td><i>house_tilted</i></td><td>10</td><td class="bold">84.86</td><td>84.34</td><td>70.35</td><td>77.09</td><td>81.13</td><td class="bold">0.3071</td><td>0.2772</td><td>0.2676</td></tr>
  <tr><td><i>house_tilted</i></td><td>15</td><td class="bold">87.27</td><td>86.99</td><td>74.63</td><td>83.83</td><td>87.48</td><td class="bold">0.3195</td><td>0.2850</td><td>0.2867</td></tr>

  <!-- office -->
  <tr><td><i>office</i></td><td>2</td><td>53.92</td><td class="bold">57.30</td><td>44.51</td><td>46.25</td><td>50.83</td><td class="bold">0.1660</td><td>0.1337</td><td>0.0915</td></tr>
  <tr><td><i>office</i></td><td>4</td><td>67.42</td><td class="bold">71.77</td><td>46.31</td><td>59.04</td><td>57.78</td><td class="bold">0.2006</td><td>0.1747</td><td>0.1007</td></tr>
  <tr><td><i>office</i></td><td>6</td><td>73.09</td><td class="bold">79.32</td><td>61.54</td><td>64.25</td><td>77.50</td><td class="bold">0.2192</td><td>0.1815</td><td>0.1443</td></tr>
  <tr><td><i>office</i></td><td>10</td><td>83.45</td><td>83.38</td><td>65.01</td><td>79.74</td><td class="bold">82.05</td><td class="bold">0.2402</td><td>0.2033</td><td>0.1839</td></tr>
  <tr><td><i>office</i></td><td>15</td><td>85.48</td><td class="bold">88.94</td><td>69.31</td><td>83.88</td><td>85.70</td><td class="bold">0.2688</td><td>0.2201</td><td>0.2244</td></tr>

  <!-- office_tilted -->
  <tr><td><i>office_tilted</i></td><td>2</td><td>45.07</td><td class="bold">58.64</td><td>44.41</td><td>46.86</td><td>32.53</td><td class="bold">0.1808</td><td>0.1473</td><td>0.0971</td></tr>
  <tr><td><i>office_tilted</i></td><td>4</td><td>49.75</td><td>56.43</td><td>50.11</td><td>51.34</td><td class="bold">57.84</td><td class="bold">0.2163</td><td>0.1732</td><td>0.1594</td></tr>
  <tr><td><i>office_tilted</i></td><td>6</td><td>63.49</td><td class="bold">71.34</td><td>53.18</td><td>66.97</td><td>61.59</td><td class="bold">0.2257</td><td>0.1859</td><td>0.1676</td></tr>
  <tr><td><i>office_tilted</i></td><td>10</td><td>71.84</td><td class="bold">80.88</td><td>56.03</td><td>72.96</td><td>72.22</td><td class="bold">0.2543</td><td>0.2236</td><td>0.2015</td></tr>
  <tr><td><i>office_tilted</i></td><td>15</td><td>83.63</td><td class="bold">86.32</td><td>63.14</td><td>80.34</td><td>80.57</td><td class="bold">0.2653</td><td>0.2257</td><td>0.2126</td></tr>

  <!-- museum -->
  <tr><td><i>museum</i></td><td>2</td><td>23.52</td><td>32.05</td><td>10.63</td><td class="bold">37.70</td><td>28.38</td><td class="bold">0.1161</td><td>0.0988</td><td>0.1055</td></tr>
  <tr><td><i>museum</i></td><td>4</td><td>37.90</td><td>49.41</td><td>21.80</td><td>41.98</td><td class="bold">54.26</td><td class="bold">0.1246</td><td>0.1006</td><td>0.0956</td></tr>
  <tr><td><i>museum</i></td><td>6</td><td>50.59</td><td class="bold">66.90</td><td>21.59</td><td>60.86</td><td>59.26</td><td class="bold">0.1435</td><td>0.1191</td><td>0.1068</td></tr>
  <tr><td><i>museum</i></td><td>10</td><td>65.76</td><td>65.63</td><td>24.85</td><td>61.48</td><td class="bold">70.62</td><td class="bold">0.1612</td><td>0.1387</td><td>0.1180</td></tr>
  <tr><td><i>museum</i></td><td>15</td><td>71.99</td><td class="bold">75.52</td><td>39.41</td><td>77.58</td><td>75.12</td><td class="bold">0.1841</td><td>0.1497</td><td>0.1245</td></tr>

  <!-- museum_tilted -->
  <tr><td><i>museum_tilted</i></td><td>2</td><td>24.47</td><td>30.81</td><td>12.39</td><td>29.69</td><td class="bold">31.63</td><td class="bold">0.1297</td><td>0.1118</td><td>0.1096</td></tr>
  <tr><td><i>museum_tilted</i></td><td>4</td><td>37.47</td><td>41.72</td><td>16.49</td><td>45.82</td><td class="bold">51.68</td><td class="bold">0.1451</td><td>0.1229</td><td>0.1257</td></tr>
  <tr><td><i>museum_tilted</i></td><td>6</td><td>46.49</td><td class="bold">63.00</td><td>28.44</td><td>47.66</td><td>57.10</td><td class="bold">0.1538</td><td>0.1361</td><td>0.1114</td></tr>
  <tr><td><i>museum_tilted</i></td><td>10</td><td>57.32</td><td class="bold">65.91</td><td>30.01</td><td>66.06</td><td>68.27</td><td class="bold">0.1748</td><td>0.1434</td><td>0.1142</td></tr>
  <tr><td><i>museum_tilted</i></td><td>15</td><td>69.12</td><td class="bold">74.24</td><td>40.99</td><td>65.72</td><td>80.32</td><td class="bold">0.1948</td><td>0.1579</td><td>0.1360</td></tr>
</table>
</div>

</body>
</html>



####
<div style="max-height:520px; overflow:auto; border:1px solid #ddd; margin:16px 0;">
<table border="1" cellpadding="4" cellspacing="0" style="border-collapse:collapse; width:100%; min-width:1200px; font-size:12px; text-align:center;">
  <caption><b>Effect of R<sub>f</sub> on CP<sub>m</sub> and F1 across environments (f<sub>e</sub>=0, T<sub>spawn</sub>=0)</b></caption>
  <thead>
    <tr>
      <th>N<sub>A</sub></th>
      <th>R<sub>f</sub></th>
      <th>Map</th>
      <th>CP<sub>m</sub> B-PP</th>
      <th>CP<sub>m</sub> B-WF</th>
      <th>CP<sub>m</sub> FSP-QT</th>
      <th>CP<sub>m</sub> FSP-G</th>
      <th>CP<sub>m</sub> FSP</th>
      <th>F1 B-PP</th>
      <th>F1 B-WF</th>
      <th>F1 FSP-QT</th>
      <th>F1 FSP-G</th>
      <th>F1 FSP</th>
    </tr>
  </thead>
  <tbody>
    <!-- N_A = 2 -->
    <tr><td>2</td><td>5</td><td><i>house_tilted</i></td><td>88.37</td><td>92.24</td><td>59.55</td><td>73.12</td><td>84.66</td><td>97.55</td><td>97.57</td><td>96.54</td><td>95.69</td><td>95.57</td></tr>
    <tr><td>2</td><td>5</td><td><i>office_tilted</i></td><td>65.95</td><td>84.82</td><td>44.70</td><td>63.11</td><td>42.49</td><td>98.25</td><td>97.55</td><td>97.89</td><td>97.70</td><td>97.50</td></tr>
    <tr><td>2</td><td>5</td><td><i>museum_tilted</i></td><td>32.31</td><td>52.07</td><td>13.79</td><td>41.87</td><td>44.05</td><td>97.95</td><td>97.11</td><td>97.62</td><td>97.90</td><td>98.10</td></tr>
    <tr><td>2</td><td>15</td><td><i>house_tilted</i></td><td>83.42</td><td>87.92</td><td>52.88</td><td>77.41</td><td>84.52</td><td>97.49</td><td>97.26</td><td>97.05</td><td>95.65</td><td>95.59</td></tr>
    <tr><td>2</td><td>15</td><td><i>office_tilted</i></td><td>65.22</td><td>86.01</td><td>49.79</td><td>59.01</td><td>41.32</td><td>98.25</td><td>97.79</td><td>97.47</td><td>97.58</td><td>97.62</td></tr>
    <tr><td>2</td><td>15</td><td><i>museum_tilted</i></td><td>41.58</td><td>52.23</td><td>13.50</td><td>40.68</td><td>38.65</td><td>98.33</td><td>97.25</td><td>97.88</td><td>98.02</td><td>98.11</td></tr>
    <tr><td>2</td><td>&infin;</td><td><i>house_tilted</i></td><td>83.42</td><td>87.92</td><td>52.88</td><td>77.41</td><td>84.52</td><td>97.49</td><td>97.26</td><td>97.05</td><td>95.65</td><td>95.59</td></tr>
    <tr><td>2</td><td>&infin;</td><td><i>office_tilted</i></td><td>65.93</td><td>85.98</td><td>49.20</td><td>59.01</td><td>41.32</td><td>98.22</td><td>97.73</td><td>97.60</td><td>97.58</td><td>97.62</td></tr>
    <tr><td>2</td><td>&infin;</td><td><i>museum_tilted</i></td><td>33.68</td><td>51.60</td><td>13.50</td><td>40.68</td><td>38.65</td><td>98.08</td><td>97.36</td><td>97.88</td><td>98.02</td><td>98.11</td></tr>

    <!-- N_A = 6 -->
    <tr><td>6</td><td>5</td><td><i>house_tilted</i></td><td>98.32</td><td>94.59</td><td>78.87</td><td>76.84</td><td>98.75</td><td>98.22</td><td>97.96</td><td>97.30</td><td>95.29</td><td>95.44</td></tr>
    <tr><td>6</td><td>5</td><td><i>office_tilted</i></td><td>90.86</td><td>97.79</td><td>64.18</td><td>79.30</td><td>78.94</td><td>98.47</td><td>98.27</td><td>98.01</td><td>97.33</td><td>97.36</td></tr>
    <tr><td>6</td><td>5</td><td><i>museum_tilted</i></td><td>67.37</td><td>67.87</td><td>33.87</td><td>58.15</td><td>80.16</td><td>98.50</td><td>97.68</td><td>97.42</td><td>97.88</td><td>97.59</td></tr>
    <tr><td>6</td><td>15</td><td><i>house_tilted</i></td><td>98.78</td><td>98.65</td><td>78.20</td><td>77.96</td><td>98.56</td><td>98.26</td><td>97.97</td><td>97.16</td><td>95.44</td><td>95.39</td></tr>
    <tr><td>6</td><td>15</td><td><i>office_tilted</i></td><td>89.55</td><td>96.67</td><td>61.77</td><td>87.72</td><td>82.69</td><td>98.34</td><td>98.33</td><td>98.08</td><td>97.28</td><td>97.20</td></tr>
    <tr><td>6</td><td>15</td><td><i>museum_tilted</i></td><td>70.58</td><td>91.14</td><td>30.41</td><td>65.81</td><td>86.70</td><td>98.37</td><td>97.74</td><td>97.80</td><td>97.67</td><td>97.45</td></tr>
    <tr><td>6</td><td>&infin;</td><td><i>house_tilted</i></td><td>98.78</td><td>98.65</td><td>78.20</td><td>77.96</td><td>98.56</td><td>98.26</td><td>97.97</td><td>97.16</td><td>95.44</td><td>95.39</td></tr>
    <tr><td>6</td><td>&infin;</td><td><i>office_tilted</i></td><td>90.77</td><td>97.12</td><td>61.81</td><td>87.72</td><td>82.69</td><td>98.31</td><td>98.36</td><td>98.02</td><td>97.28</td><td>97.20</td></tr>
    <tr><td>6</td><td>&infin;</td><td><i>museum_tilted</i></td><td>68.03</td><td>88.99</td><td>32.54</td><td>65.51</td><td>85.08</td><td>98.45</td><td>97.92</td><td>97.81</td><td>97.69</td><td>97.49</td></tr>

    <!-- N_A = 15 -->
    <tr><td>15</td><td>5</td><td><i>house_tilted</i></td><td>99.14</td><td>98.90</td><td>93.05</td><td>99.32</td><td>98.49</td><td>98.52</td><td>97.92</td><td>97.53</td><td>95.29</td><td>95.58</td></tr>
    <tr><td>15</td><td>5</td><td><i>office_tilted</i></td><td>96.84</td><td>97.82</td><td>81.27</td><td>97.64</td><td>97.73</td><td>98.48</td><td>98.53</td><td>98.36</td><td>97.03</td><td>97.02</td></tr>
    <tr><td>15</td><td>5</td><td><i>museum_tilted</i></td><td>93.96</td><td>95.76</td><td>65.52</td><td>91.61</td><td>99.17</td><td>98.63</td><td>98.03</td><td>98.11</td><td>97.33</td><td>97.24</td></tr>
    <tr><td>15</td><td>15</td><td><i>house_tilted</i></td><td>99.14</td><td>98.88</td><td>89.75</td><td>98.81</td><td>98.32</td><td>98.56</td><td>97.74</td><td>97.46</td><td>95.52</td><td>95.60</td></tr>
    <tr><td>15</td><td>15</td><td><i>office_tilted</i></td><td>98.04</td><td>97.87</td><td>78.35</td><td>97.79</td><td>98.32</td><td>98.52</td><td>98.43</td><td>98.05</td><td>96.99</td><td>97.01</td></tr>
    <tr><td>15</td><td>15</td><td><i>museum_tilted</i></td><td>92.90</td><td>96.92</td><td>50.17</td><td>92.80</td><td>99.72</td><td>98.68</td><td>98.18</td><td>97.48</td><td>97.33</td><td>97.22</td></tr>
    <tr><td>15</td><td>&infin;</td><td><i>house_tilted</i></td><td>99.14</td><td>98.88</td><td>89.75</td><td>98.81</td><td>98.32</td><td>98.56</td><td>97.74</td><td>97.46</td><td>95.52</td><td>95.60</td></tr>
    <tr><td>15</td><td>&infin;</td><td><i>office_tilted</i></td><td>98.05</td><td>98.00</td><td>73.65</td><td>97.79</td><td>98.32</td><td>98.54</td><td>98.46</td><td>98.17</td><td>96.99</td><td>97.01</td></tr>
    <tr><td>15</td><td>&infin;</td><td><i>museum_tilted</i></td><td>96.63</td><td>97.63</td><td>49.50</td><td>93.00</td><td>99.48</td><td>98.68</td><td>98.11</td><td>97.53</td><td>97.34</td><td>97.28</td></tr>
  </tbody>
</table>
</div>

<p style="font-size:12px; margin-top:-8px;">
  <i>Note.</i> Standard deviations: 0.04–1.19 for CP<sub>m</sub> and 0.09–0.33 for F1.
</p>








##########################


<h3 id="performance-metrics">Performance Metrics</h3>
<p>
All experiments were repeated 5 times, with random seeds 1–5, and the average of each metric was taken over all repetitions. While their deployment position was constant, each agent’s deployment orientation was randomized for each repetition.
We ran experiments with varying swarm sizes \(N_A\) of 2, 4, 6, 10, and 15 agents.
</p>

<h4 id="coverage-metrics">Coverage Metrics</h4>
<p>
Coverage is a significant metric for exploration. The coverage percentage \(CP(t)\) at time \(t\) is defined as:
</p>

$$
CP(t) \;=\; \frac{N_{cc}(t)\,\rho^2}{AA}
$$

<p>
where \(N_{cc}(t)\) is the number of covered cells in the agent’s map. Note that when there are pose estimation or distance sensor inaccuracies, cells outside the map borders or in \(IA\) might be added to an agent’s map. These are counted towards \(N_{cc}\). Cells merged by our algorithm are divided into cells of size \(\rho\).
</p>

<p>
We also compare the coverage metric of the final gathered map from the agent, in which we ignore cells outside the arena and in \(IA\):
</p>

$$
CP_m \;=\; \frac{N_{mc}\,\rho^2}{AA}
$$

<p>
where \(N_{mc}\) is the number of covered cells inside the map boundaries and outside \(IA\) in the map.
</p>

<p>
To compare which configuration results in the fastest increase in coverage, we also include the average coverage percentage during the mission, \(ACP\):
</p>

$$
ACP \;=\; \frac{\sum_{t=0}^{T_{\mathrm{end}}} CP(t)}{T_{\mathrm{end}}}
$$

<p>
As officially FSP considers cells with fully evaporated pheromones uncovered, we include previously covered but evaporated pheromone-cells in \(N_{cc}\) for a fair comparison.
</p>

<h4 id="confidence-metrics">Confidence Metrics</h4>
<p>
For BICLARE it is interesting to observe the average certainty at time \(t\), \(AC(t)=\left|\varphi(z,t)-0.5\right|\).
To compare which configuration can ensure the highest overall certainty, we define the mean average certainty during the entire mission:
</p>

$$
AAC \;=\; \frac{\sum_{t=0}^{T_{\mathrm{end}}} AC(t)}{T_{\mathrm{end}}}
$$

<h4 id="mapping-accuracy">Mapping accuracy</h4>
<p>
To evaluate the accuracy of the created maps, we use the precision and recall metrics. Here, we define cell \(z\) in a generated map to be an obstacle cell if \(\varphi(z,t)<0.5\), and free if \(\varphi(z,t)\ge 0.5\).
Splitting the actual map up in cells of size \(\rho\), we define cells to be truly occupied when obstacles cover 10\% of their area.
Given the number of correctly identified obstacle cells \(TP\), falsely identified obstacle cells \(FP\), and falsely identified free cells \(FN\):
</p>

$$
\text{precision} \;=\; \frac{TP}{TP + FP}
$$

<p>and</p>

$$
\text{recall} \;=\; \frac{TP}{TP + FN}
$$

<p>
To determine \(TP\), \(FP\), and \(FN\), only cells in \(N_{cc}\) that were at any point reachable during the experiment are considered.
To get a more general impression of the accuracy of the created map for comparison between algorithms, we use the \(F_1\)-score, which is the harmonic mean of precision and recall:
</p>

$$
F_1 \;=\; \frac{2 \cdot \text{precision} \cdot \text{recall}}{\text{precision} + \text{recall}}
$$

<p>
For each experiment, we take the map of the agent who finished first \((S_i = 4)\), at its finish time.
</p>

<h4 id="obstacle-avoidance">Obstacle avoidance</h4>
<p>
We report the number of agent–obstacle collisions and the number of inter-agent collisions. The former shows the average collisions with static or dynamic obstacles per agent. The latter is also shown on average per agent, meaning that two agents colliding is one inter-agent collision per agent.
</p>

<h4 id="efficiency">Efficiency</h4>
<p>
To determine the efficiency of our algorithm, we compare the total travelled path and estimated battery usage by each agent throughout the mission. The battery estimation is based on the estimated power drawn by the motors and from sending and exchanging messages.
We also track the distribution of observations throughout the map by counting the number of times each cell is observed. One observation of a cell is defined as a sensor ray crossing or being intersected in that cell.
To determine the memory efficiency of our quadtree, we compare the number of quadtree nodes with the number of cells in the map if it were a matrix.
</p>

<h4 id="return-rate">Return rate</h4>
<p>
We report the number of swarm agents that successfully returned to the deployment site.
We define a successful return for agent \(A_i\) when \(\left\lVert p_i - p_{i,t_0} \right\rVert < 2\,\text{m}\).
</p>







