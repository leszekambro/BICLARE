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



<style>
  table {
    border-collapse: collapse;
    width: 100%;
    font-size: 12px;
  }
  th, td {
    border: 1px solid #ccc;
    padding: 4px 6px;
    text-align: center;
  }
  th {
    background-color: #f2f2f2;
    font-weight: bold;
  }
  caption {
    caption-side: top;
    font-weight: bold;
    margin-bottom: 6px;
  }
  tr:nth-child(even) {
    background-color: #fafafa;
  }
  .bold {
    font-weight: bold;
  }
</style>

<table>
  <caption>Performance of different algorithms across all maps and swarm sizes, for <i>f<sub>e</sub>=0</i></caption>
  <thead>
    <tr>
      <th rowspan="2">Map</th>
      <th rowspan="2">N<sub>A</sub></th>
      <th colspan="5">ACP</th>
      <th colspan="3">AAC</th>
    </tr>
    <tr>
      <th>BICLARE-PP</th>
      <th>BICLARE-WF</th>
      <th>FSP-QT</th>
      <th>FSP-G</th>
      <th>FSP</th>
      <th>BICLARE-PP</th>
      <th>BICLARE-WF</th>
      <th>FSP-QT</th>
    </tr>
  </thead>
  <tbody>
    <tr><td rowspan="5"><i>house</i></td><td>2</td><td class="bold">69.40</td><td>66.68</td><td>49.12</td><td>61.19</td><td>61.68</td><td class="bold">0.2023</td><td>0.2001</td><td>0.1543</td></tr>
    <tr><td>4</td><td class="bold">82.74</td><td>78.30</td><td>68.23</td><td>70.00</td><td>69.33</td><td class="bold">0.2450</td><td>0.2259</td><td>0.1849</td></tr>
    <tr><td>6</td><td class="bold">84.78</td><td>84.41</td><td>75.09</td><td>75.77</td><td>77.05</td><td class="bold">0.2733</td><td>0.2420</td><td>0.1977</td></tr>
    <tr><td>10</td><td>84.65</td><td>85.67</td><td>80.47</td><td>84.49</td><td class="bold">86.71</td><td class="bold">0.3053</td><td>0.2769</td><td>0.2551</td></tr>
    <tr><td>15</td><td class="bold">88.73</td><td>87.77</td><td>84.56</td><td>85.44</td><td>87.47</td><td class="bold">0.3203</td><td>0.2896</td><td>0.2812</td></tr>

    <tr><td rowspan="5"><i>house_tilted</i></td><td>2</td><td>61.01</td><td class="bold">69.86</td><td>43.69</td><td>56.87</td><td>63.91</td><td class="bold">0.2145</td><td>0.2002</td><td>0.1979</td></tr>
    <tr><td>4</td><td>75.80</td><td class="bold">79.37</td><td>56.19</td><td>71.58</td><td>72.29</td><td class="bold">0.2470</td><td>0.2342</td><td>0.2191</td></tr>
    <tr><td>6</td><td>80.11</td><td>81.25</td><td>63.43</td><td>64.11</td><td class="bold">75.41</td><td class="bold">0.2730</td><td>0.2550</td><td>0.2423</td></tr>
    <tr><td>10</td><td class="bold">84.86</td><td>84.34</td><td>70.35</td><td>77.09</td><td>81.13</td><td class="bold">0.3071</td><td>0.2772</td><td>0.2676</td></tr>
    <tr><td>15</td><td class="bold">87.27</td><td>86.99</td><td>74.63</td><td>83.83</td><td>87.48</td><td class="bold">0.3195</td><td>0.2850</td><td>0.2867</td></tr>
    <!-- (Analogicznie dodaj pozostałe sekcje: office, office_tilted, museum, museum_tilted) -->
  </tbody>
</table>





