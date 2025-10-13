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

