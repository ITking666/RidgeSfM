# ScanNet scene 0710 - frame skip _k=30_

The videos below show RidgeSfM reconstructions for ScanNet test scene 0710 (using all frames).

For each scene, we use the reconstructed depth and camera parameters to reproject the pixels to form a point cloud.
Each point in the cloud has the form _(x,y,z,r,g,b)_ ∈ ℝ<sup>6</sup>.
To simplify the point-cloud, we use K-Means to extract 100,000 centroids.

<table style="table-layout: fixed; width: 100%;">
<thead>
  <tr>
    <th colspan="2">For each video</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Top left: the rendered point cloud.<br></td>
    <td>Top right: The focal-plane trajectory for the predicted camera locations.</td>
  </tr>
  <tr>
    <td>Bottom left: The input video.</td>
    <td>Bottom right: The focal-plane trajectory of the ground truth camera locations.</td>
  </tr>
  <tr>
  <td colspan="2">
<a href="https://drive.google.com/file/d/1DfBu2_WlJ6upfvNtTpUXyoRt_6GG9Xo4/view?usp=sharing" title="RidgeSfm - ScanNet scene 0710 frameskip k=30"><img src="scene3_frameskip30.jpg" alt="RidgeSfm - ScanNet scene 0710 frameskip k=30" /></a>
</td>
  </tr>
</tbody>

<thead>
  <tr>
    <th colspan="2">Using MeshLab to display the point cloud <a href="scene3_frameskip30.ply"> PLY file </a></th>
  </tr>
</thead>

<tr>
<td><img src="scene3_0.png" width="320" alt="ScanNet reconstruction" /></td>
<td><img src="scene3_1.png" width="320" alt="ScanNet reconstruction" /></td>
</tr>
<tr>
<td><img src="scene3_2.png" width="320" alt="ScanNet reconstruction" /></td>
<td><img src="scene3_3.png" width="320" alt="ScanNet reconstruction" /></td>
</tr>
</table>
