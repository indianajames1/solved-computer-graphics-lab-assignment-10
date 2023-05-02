Download Link: https://assignmentchef.com/product/solved-computer-graphics-lab-assignment-10
<br>



+ LabAssignment2/

+ 1/

<ul>

 <li>py</li>

</ul>

+ 2/

<ul>

 <li>py</li>

</ul>

+ 3/

<ul>

 <li>py</li>

</ul>




<ul>

 <li>The submission time is determined not when the commit is made but when the git push is made.</li>

</ul>




<ol>

 <li>Write down a Python program to compare 4 orientation interpolation methods. A.First, implement following functions:</li>

 <li>exp &amp; log functions</li>

 <li><strong> exp(rv) </strong>

  <ol>

   <li>Converts a rotation vector to a rotation matrix</li>

   <li>You can use Rodrigues’ rotation formula or the method in 10-Animation slides.</li>

   <li>Returns a rotation matrix <strong> log(R) </strong></li>

  </ol></li>

 <li>Converts a rotation matrix to a rotation vector</li>

 <li>You can use the method in 10-Animation slides.</li>

 <li>Returns a rotation vector (the length of the vector is the rotation angle) C.Interpolation functions:</li>

 <li><strong>slerp(R1, R2, t)</strong> – slerp</li>

</ol>

<ul>

 <li>R1 &amp; R2: rotation matrices for start &amp; end orientations ii. <strong>interpolateRotVec(rv1, rv2, t)</strong> – interpolate each element of two vectors</li>

</ul>

<ol>

 <li>rv1 &amp; rv2: rotation vectors for start &amp; end orientations</li>

</ol>

<ol>

 <li><strong>interpolateZYXEulerAngles(euler1, euler2, t)</strong> – interpolate each element of two euler angle tuples

  <ul>

   <li>euler1 &amp; euler2: tuples of ZYX Euler angles for start &amp; end orientations (euler1[0]:</li>

  </ul></li>

</ol>

xang, euler1[1]: yang, euler1[2]: zang)

<ol>

 <li><strong>interpolateRotMat(R1, R2, t)</strong> – interpolate each element of two matrices

  <ul>

   <li>R1 &amp; R2: rotation matrices for start &amp; end orientations D. For all interpolation functions:</li>

  </ul></li>

</ol>

<ol>

 <li>All interpolation functions return a rotation matrix ii.The parameter t ranges from 0.0 to 1.0</li>

</ol>

<ol>

 <li>Start from the uploaded code skeleton (LabAssignment10-1-code-skeleton.py).</li>

 <li>You will need to use</li>

 <li>The given lerp() for interpolateRotVec(), interpolateZYXEuler(), interpolateRotMat() ii.The given ZYXEulerToRotMat() for interpolateZYXEuler() iii.      Your exp(), log() implementation for slerp(), interpolateRotVec() G.Program usage (already implemented in the code skeleton):</li>

 <li>When the program is run, only slerp() result is visible ii.A key: Toggle slerp() result iii.   S key: Toggle interpolateRotVec() result iv.       D key: Toggle interpolateZYXEuler() result</li>

 <li>F key: Toggle interpolateRotMat() result vi.Z key: Hide all results vii.          X key: Show all results</li>

 <li>Set the window title to <strong>your student ID</strong> and the window size to (480,480).</li>

 <li>Expected result: Uploaded LabAssignment10-1.mp4</li>

 <li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)</li>

</ol>


