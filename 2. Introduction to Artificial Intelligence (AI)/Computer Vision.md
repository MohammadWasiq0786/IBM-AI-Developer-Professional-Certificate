<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="https://unpkg.com/@highlightjs/cdn-assets@10.7.1/styles/default.min.css">
  </head>
  <body>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-AI0101EN-SkillsNetwork/labs/Module2/images/IDSNlogo.png" width="200" height="200">
    <h2>Hands-On Lab: Computer Vision (20 Mins)</h2>
    <p>Objective for Exercise:</p>
    <ul>
      <li>Learn about IBM’s Adversarial Robustness Toolbox, and use it to mitigate simulated attacks by hackers..</li>
    </ul>
    <h1>Computer Vision</h1>
    <p>IBM Research creates innovative tools and resources to help unleash the power of AI.</p>
    <p><strong>Follow these steps to explore the demo:</strong></p>
    <ol>
      <li>
        <p>Access the demo here:<a href="https://art-demo.mybluemix.net/?utm_medium=Exinfluencer&#x26;utm_source=Exinfluencer&#x26;utm_content=000026UJ&#x26;utm_term=10006555&#x26;utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkAI0101ENSkillsNetwork20718152-2022-01-01&#x26;cm_mc_uid=59963159489715526067556&#x26;cm_mc_sid_50200000=57143911561485594784&#x26;cm_mc_sid_52640000=48611511561485594790" target="_blank" rel="external">Your AI model might be telling you this is not a cat.</a></p>
      </li>
      <li>
        <p>In the <strong>Try it out</strong> section, click the image of the Siamese cat.</p>
      </li>
    </ol>
    <p><em>Figure 1 - Select an image</em></p>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-AI0101EN-SkillsNetwork/labs/Module2/images/4.png" width="600">
    <ol start="3">
      <li>In the <strong>Simulate Attack</strong> section, ensure that no attack is selected, and that all the sliders are to the far left, indicating that all attacks and mitigation strategies are turned off.</li>
    </ol>
    <p>What does Watson identify the image as, and at what confidence level? E.g. Siamese cat 92%</p>
    <ol start="4">
      <li>In the <strong>Simulate Attack</strong> section, under <strong>Adversarial noise type</strong>, select <strong>Fast Gradient Method</strong>. The strength slider will move to low.</li>
    </ol>
    <p><em>Figure 2 - Select an attack and level</em></p>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-AI0101EN-SkillsNetwork/labs/Module2/images/5.png" width="600">
    <p>What does Watson identify the image as now, and at what confidence level?</p>
    <ol start="5">
      <li>In the <strong>Defend attack</strong> section, move the <strong>Gaussian Noise</strong> slider to low.</li>
    </ol>
    <p><em>Figure 3 - Mitigate the attack</em></p>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-AI0101EN-SkillsNetwork/labs/Module2/images/6.png" width="600">
    <ol start="6">
      <li>What does Watson identify the image as now, and at what confidence level? Did the image recognition improve?</li>
    </ol>
    <p><em>Figure 4 - View the results</em></p>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-AI0101EN-SkillsNetwork/labs/Module2/images/7.png" width="600">
    <p>Note that you can use the slider on the image to see the original and modified images.</p>
    <ol start="7">
      <li>
        <p>Move the <strong>Gaussian Noise</strong> slider to <strong>medium</strong>, and then to <strong>high</strong>. For each level, note what Watson identifies the image as, and at what confidence level. Did the image recognition improve?</p>
      </li>
      <li>
        <p>Move the <strong>Gaussian Noise</strong> slider to <strong>None</strong>.</p>
      </li>
      <li>
        <p>In the <strong>Defend attack</strong> section, move the <strong>Spatial Smoothing</strong> slider to <strong>low</strong>. What does Watson identify the image as now, and at what confidence level? Did the image recognition improve?</p>
      </li>
      <li>
        <p>Move the <strong>Spatial Smoothing</strong> slider to <strong>medium</strong>, and then to <strong>high</strong>. For each level, note what Watson identifies the image as, and at what confidence level. Did the image recognition improve?</p>
      </li>
      <li>
        <p>Move the <strong>Spatial Smoothing</strong> slider to <strong>None</strong>.</p>
      </li>
      <li>
        <p>In the <strong>Defend attack</strong> section, move the <strong>Feature Squeezing</strong> slider to <strong>low</strong>. What does Watson identify the image as now, and at what confidence level? Did the image recognition improve?</p>
      </li>
      <li>
        <p>Move the <strong>Feature Squeezing</strong> slider to <strong>medium</strong>, and then to <strong>high</strong>. For each level, note what Watson identifies the image as, and at what confidence level. Did the image recognition improve?</p>
      </li>
      <li>
        <p>Which of the three defenses would you use to defend against a Fast Gradient Attack?</p>
      </li>
    </ol>
    <p><strong>Optional:</strong></p>
    <p>If you have time, use the same techniques to explore the other methods of attack (Projected Gradient Descent and C&#x26;W Attack) and evaluate which method of defense works best for each. If you want, try a different image.</p>
    <p>Use the Discussion Forum to talk about the attacks and mitigation strategies with your fellow students.</p>
    <h2>Author(s)</h2>
    <p><a href="https://www.linkedin.com/in/ravahuja/?utm_medium=Exinfluencer&#x26;utm_source=Exinfluencer&#x26;utm_content=000026UJ&#x26;utm_term=10006555&#x26;utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkAI0101ENSkillsNetwork20718152-2022-01-01" target="_blank" rel="external">Rav Ahuja</a></p>
    <h2>Changelog</h2>
    <table>
      <thead>
        <tr>
          <th>Date</th>
          <th>Version</th>
          <th>Changed by</th>
          <th>Change Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2020-08-27</td>
          <td>2.0</td>
          <td>Anamika</td>
          <td>Migrated Lab to Markdown and added to course repo in GitLab</td>
        </tr>
        <tr>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
        </tr>
      </tbody>
    </table>
    <h2></h2>
    <h3 align="center">© IBM Corporation 2020. All rights reserved.</h3>
    <h3></h3>
    <script>window.addEventListener('load', function() {
snFaculty.inject();
});</script>
    <script src="https://skills-network-assets.s3.us.cloud-object-storage.appdomain.cloud/scripts/inject.43989f87.js"></script>
    <script src="https://unpkg.com/@highlightjs/cdn-assets@10.7.1/highlight.min.js"></script>
    <script src="https://unpkg.com/highlightjs-badge@0.1.9/highlightjs-badge.min.js"></script>
  </body>
</html>
