<!-- Animated Slider Start -->
<div align="center">

<style>
.slider-container {
  width: 90%;
  max-width: 700px;
  overflow: hidden;
  border-radius: 14px;
  background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
  box-shadow: 0 10px 30px rgba(0,0,0,0.4);
  color: white;
  font-family: Arial, sans-serif;
}

.slider {
  display: flex;
  width: 300%;
  animation: slide 12s infinite;
}

.slide {
  width: 100%;
  padding: 35px;
  text-align: center;
}

.slide h2 {
  margin-bottom: 10px;
  font-size: 22px;
}

.slide p {
  font-size: 15px;
  opacity: 0.9;
}

@keyframes slide {
  0% { transform: translateX(0); }
  33% { transform: translateX(0); }
  38% { transform: translateX(-100%); }
  66% { transform: translateX(-100%); }
  71% { transform: translateX(-200%); }
  100% { transform: translateX(-200%); }
}
</style>

<div class="slider-container">
  <div class="slider">

    <div class="slide">
      <h2>🛡️ Cyber Threat Researcher</h2>
      <p>Focused on real-world security research, vulnerability analysis, and threat intelligence.</p>
    </div>

    <div class="slide">
      <h2>🌐 Web3 & Smart Contracts</h2>
      <p>Learning Ethereum, Solidity, and decentralized application security.</p>
    </div>

    <div class="slide">
      <h2>🧠 Python & Linux</h2>
      <p>Automation, scripting, and security tooling with clean and efficient code.</p>
    </div>

  </div>
</div>

</div>
<!-- Animated Slider End -->
