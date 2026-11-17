# Łukasz Musiał | musialny.dev

Software Engineer – Data Visualization & Cloud Infrastructure | Embedded & EV Electronics (DGUV 3E, SEP G1)

Software engineer working across data visualization, cloud infrastructure
and HV & LV control systems for electric vehicles.

---

## Work

### [@blacklabel](https://github.com/blacklabel) (2025 – present)

Data visualization software.

#### Seconded to Deepflare – FlareDesigner (2025–2026)
<table>
  <tr>
    <td width="50%" style="text-align: right;">
      <img src="1acb.png"
           alt="1ACB Render with Cartoon Shading"
           style="max-width: 100%;">
    </td>
    <td width="50%">
      <p>
        FlareDesigner – a platform giving biologists without a technical background access to biotech ML models.
      </p>
      <ul>
        <li>Developed the entire frontend</li>
        <li>Built views of model results for biologists: filterable tables and charts for separating meaningful results from noise</li>
        <li>Integrated interactive 3D molecular visualization (<a href="https://molstar.org/">Mol*</a>)</li>
        <li>Developed backend microservices, including services wrapping model-running code and exposing a fixed set of parameters</li>
        <li>Set up CI/CD, the GCP configuration (mainly Cloud Run) and Kubernetes clusters on OVH</li>
        <li>Took over the orchestrator service that starts model runners on demand and runs them in parallel under load</li>
      </ul>
    </td>
  </tr>
</table>

---

### PK MechPower – Formula Student

<table>
  <tr>
    <td width="50%">
      <p>
        EV HV &amp; LV control systems of an electric race car.
      </p>
      <ul>
        <li>Overall control system architecture</li>
        <li>Vehicle software architecture</li>
        <li>Schematic and PCB design, including:
          <ul>
            <li>Shutdown Circuit control logic safety PCB</li>
            <li>High-power carrier board for the isolated HV–LV DC–DC converter</li>
            <li>LV power stage switching board: LV high-power DC–DC converter, battery ↔ SMPS power distribution</li>
            <li>Development PCBs for integrators testing the car's systems</li>
            <li>Subsystem circuits with open- and short-circuit detection, etc.</li>
          </ul>
        </li>
        <li>Schematic and PCB design reviews</li>
        <li>Review and implementation of embedded software and tests</li>
        <li>Technical support for the HV tractive system integration</li>
      </ul>
    </td>
    <td width="50%" style="text-align: right;">
      <img src="Formula%C2%A0Student%20Car%20image%20created%20by%20Media'n'Design%20section%20at%20PK%20MechPower.jpg" alt="Formula Student Car image created by Media'n'Design section at PK MechPower" style="max-width: 100%;">
    </td>
  </tr>
</table>

---

## Certifications

| Certification | Scope |
|---|---|
| ![DGUV 3E](https://img.shields.io/badge/DGUV_209--093-3E-orange) | Live work on high-voltage vehicle systems |
| ![DGUV 2E](https://img.shields.io/badge/DGUV_209--093-2E-orange) | Work on de-energized high-voltage vehicle systems |
| ![SEP](https://img.shields.io/badge/SEP_G1%2FE-%E2%89%A41_kV-blue) | Operation of electrical installations and equipment up to 1 kV |

---

## Stack

**Software:** TypeScript, Vue.js, Nuxt, C++, C | Build tooling: Webpack, Vite, CMake<br>
<sub>Also familiar with the Elixir / Phoenix and Erlang ecosystems.</sub>

**Infrastructure (DevOps / SysOps):** Linux, Docker, Kubernetes, LXD/LXC, Proxmox, GCP (Cloud Run)

**Embedded & hardware:** ARM / RISC-V (ESP32, RPi Pico, STM32), AVR | C, CMake, Clang/LLVM, GCC | Altium Designer (PCB) | SPICE, SI/PI, EMI/EMC | VHDL, SystemVerilog (FPGA)

### Exploring

**Computer graphics:** Vulkan, WebGL, WebGPU

**ML:** model inference, training and fine-tuning

**ASIC design:** analog and digital (XSchem, ngspice, KLayout)

---

## Projects

### CAN_Devboard

<img src="can_devboard_render.png" alt="Render of the CAN_Devboard" width="300">

A board for testing multiple devboards and external devices on a CAN bus, used by the PK MechPower team.

In progress: vehicle telemetry (ESP32, live view), which will become
the base of a universal vehicle module with extension boards.
