<h1>Rocket-Booster</h1>

<h2>Overview</h2>
<p>Rocket-Booster is a thrilling Unity-based game where players must navigate a rocket from point A to point B while avoiding obstacles. The game features multiple levels with increasing difficulty, requiring precision and skill to progress. Players must use thrust and rotation controls to maneuver through challenging environments and reach the finish point safely.</p>

<h2>How to Play</h2>
<ul>
  <li>Press <strong>Spacebar</strong> (or assigned thrust key) to activate the rocket's booster and move upward.</li>
  <li>Use <strong>Left Arrow</strong> and <strong>Right Arrow</strong> keys (or assigned rotation controls) to steer the rocket.</li>
  <li>Avoid colliding with obstacles; hitting them will restart the level.</li>
  <li>Reach the designated landing zone (Finish) to progress to the next level.</li>
  <li>Friendly objects are safe to touch and do not cause the rocket to crash.</li>
</ul>

<h2>Features</h2>
<ul>
  <li><strong>Realistic Physics:</strong> Uses Unity’s Rigidbody system for smooth and accurate movement.</li>
  <li><strong>Multiple Levels:</strong> Players advance through progressively challenging levels.</li>
  <li><strong>Dynamic Obstacle Avoidance:</strong> Various moving and stationary obstacles increase difficulty.</li>
  <li><strong>Immersive Audio:</strong> Rocket thrust sound effects for a realistic experience.</li>
  <li><strong>Level Restart & Progression:</strong> Automatically restarts on collision and progresses upon successful landing.</li>
</ul>

<h2>Scripts Used</h2>
<ul>
  <li><strong>CollisionHandler.cs</strong>
    <ul>
      <li>Handles rocket collisions with obstacles, friendly objects, and the finish line.</li>
      <li>Restarts the level if the player crashes.</li>
      <li>Advances to the next level upon reaching the finish point.</li>
    </ul>
  </li>
  <li><strong>Movement.cs</strong>
    <ul>
      <li>Controls player movement using thrust and rotation.</li>
      <li>Applies force for upward motion and rotation for directional control.</li>
      <li>Includes smooth rotation handling for better gameplay experience.</li>
      <li>Manages rocket engine audio playback.</li>
    </ul>
  </li>
</ul>

<h2>Technologies & Tools Used</h2>
<ul>
  <li><strong>Game Engine:</strong> Unity</li>
  <li><strong>Programming Language:</strong> C#</li>
  <li><strong>Physics Engine:</strong> Unity’s Rigidbody system</li>
  <li><strong>Audio:</strong> Unity AudioSource for thrust sound effects</li>
</ul>

<h2>How to Run the Game</h2>
<pre><code>git clone https://github.com/M-Shaharyar/Rocket-Booster.git</code></pre>
<p>Open the project in Unity.</p>
<p>Press the Play button in the Unity Editor.</p>
<p>Use the movement controls to navigate the rocket through obstacles.</p>

<h2>Contribution</h2>
<p>Contributions are always welcome! Feel free to fork the repository, make improvements, and submit a pull request.</p>

<h2>License</h2>
<p>This project is open-source and available under the <strong>MIT License</strong>.</p>
