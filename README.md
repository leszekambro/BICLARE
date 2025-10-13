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

<div style="overflow-x: auto;">
<table style="border-collapse: collapse; font-size: 12px; text-align: center; width: 100%;">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th rowspan="2">Map</th>
      <th rowspan="2">N<sub>A</sub></th>
      <th colspan="5">ACP</th>
      <th colspan="3">AAC</th>
    </tr>
    <tr style="background-color: #f9f9f9;">
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

    <tr>
      <td rowspan="5"><b>house</b></td>
      <td>2</td><td><b>69.40</b></td><td>66.68</td><td>49.12</td><td>61.19</td><td>61.68</td><td><b>0.2023</b></td><td>0.2001</td><td>0.1543</td>
    </tr>
    <tr>
      <td>4</td><td><b>82.74</b></td><td>78.30</td><td>68.23</td><td>70.00</td><td>69.33</td><td><b>0.2450</b></td><td>0.2259</td><td>0.1849</td>
    </tr>
    <tr>
      <td>6</td><td><b>84.78</b></td><td>84.41</td><td>75.09</td><td>75.77</td><td>77.05</td><td><b>0.2733</b></td><td>0.2420</td><td>0.1977</td>
    </tr>
    <tr>
      <td>10</td><td>84.65</td><td>85.67</td><td>80.47</td><td>84.49</td><td><b>86.71</b></td><td><b>0.3053</b></td><td>0.2769</td><td>0.2551</td>
    </tr>
    <tr>
      <td>15</td><td><b>88.73</b></td><td>87.77</td><td>84.56</td><td>85.44</td><td>87.47</td><td><b>0.3203</b></td><td>0.2896</td><td>0.2812</td>
    </tr>

    <tr style="background-color:#f9f9f9;">
      <td rowspan="5"><b>museum</b></td>
      <td>2</td><td>23.52</td><td>32.05</td><td>10.63</td><td><b>37.70</b></td><td>28.38</td><td><b>0.1161</b></td><td>0.0988</td><td>0.1055</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>4</td><td>37.90</td><td>49.41</td><td>21.80</td><td>41.98</td><td><b>54.26</b></td><td><b>0.1246</b></td><td>0.1006</td><td>0.0956</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>6</td><td>50.59</td><td><b>66.90</b></td><td>21.59</td><td>60.86</td><td>59.26</td><td><b>0.1435</b></td><td>0.1191</td><td>0.1068</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>10</td><td>65.76</td><td>65.63</td><td>24.85</td><td>61.48</td><td><b>70.62</b></td><td><b>0.1612</b></td><td>0.1387</td><td>0.1180</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>15</td><td>71.99</td><td><b>75.52</b></td><td>39.41</td><td>77.58</td><td>75.12</td><td><b>0.1841</b></td><td>0.1497</td><td>0.1245</td>
    </tr>

  </tbody>
</table>
</div>





