# QUANTUM PHOTON

**The Threshold That Creates the Quantum: Photoemission, Attosecond Boundary Crossings, and the Work Function as Conditional Independence Surface in $\mathrm{TH}(a,d)$**

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone*

> "On the production and transformation of light from a heuristic point of view." — A. Einstein, *Annalen der Physik* **17**, 132–148, 1905
>
> "The observed emergence of coherence in secondary photoemission points to the development of an underlying novel process on top of those encompassed in the current theoretical photoemission framework." — Hong, Zou, Ran et al., *Nature*, 2023
>
> "The photoelectric effect explained by Einstein is often regarded as a one-electron phenomenon, whereas the interaction of the escaping electron with other electrons, referred to as electron correlation, plays an important role." — Alexandridi et al., *Phys. Rev. Lett.*, 2025

---

## Abstract

Einstein's 1905 photoelectric equation — $E_k = h\nu - \phi$ — is the simplest equation in quantum physics. A photon of frequency $\nu$ strikes a metal surface with work function $\phi$. If $h\nu > \phi$, an electron is ejected with kinetic energy $E_k = h\nu - \phi$. If $h\nu < \phi$, nothing happens, regardless of the intensity of the light. No classical explanation accounts for this threshold. The threshold creates the quantum.

This framework proposes that the work function $\phi$ is not merely a material parameter. It is the simplest realization of the conditional independence boundary — the same mathematical object that appears as the event horizon in gravitational physics, the Markov blanket in active inference, the mass splitting $\delta$ in dSphobic dark matter, and the $\varepsilon$-threshold in $\mathrm{TH}(a,d)$. Below the threshold, the electron is screened from the vacuum — conditionally independent of the exterior given the boundary. Above the threshold, the electron crosses the boundary and carries Fisher information about the photon into the observable sector.

Six recent results transform the century-old photoelectric effect from a textbook demonstration into a frontier of quantum physics: (1) attosecond X-ray photoemission delays up to 700 as at SLAC's LCLS, nearly twice the theoretical prediction, revealing that the boundary crossing is governed by electron–electron correlations (2024–2026); (2) the identification of electron correlation as the dominant factor in photoemission timing, solving a long-standing inconsistency (*Phys. Rev. Lett.*, October 2025); (3) the discovery that quantum efficiency of photoemission increases by orders of magnitude with few-cycle optical pulses (*Phys. Rev. Research* **8**, January 2026); (4) the first demonstration that genuinely quantum light — bright squeezed vacuum with zero mean electric field — drives strong-field photoemission (*Nature Physics*, November 2025); (5) the observation of unexpected coherence in secondary photoemission from strontium titanate, challenging the three-step model (*Nature*, 2023); and (6) the measurement of 300-attosecond internal photoemission across a graphene–silicon carbide Schottky junction, opening the door to petahertz electronics (*Nature Photonics*, 2020).

Eight formal correspondences connect the photoelectric threshold to the $\mathrm{TH}(a,d)$ architecture. Four predictions follow.

---

## Part I · The Threshold

### I.1 Hertz, Hallwachs, and the Discovery

In 1887, Heinrich Hertz observed that ultraviolet light facilitated the discharge of sparks between electrodes (*Ann. Phys.* **267**, 983, 1887). In 1888, Wilhelm Hallwachs showed that ultraviolet light falling on a clean zinc plate caused it to lose negative charge. Philipp Lenard (1902) established the quantitative facts that shattered classical electromagnetism: the maximum kinetic energy of emitted electrons depends on the *frequency* of the light, not its intensity; below a threshold frequency, no electrons are emitted regardless of intensity; and the emission is effectively instantaneous.

Classical electromagnetic theory predicted that energy would accumulate continuously in the electron until it had enough to escape, that higher intensity should produce higher-energy electrons, and that dim light should cause a measurable delay. All three predictions failed. The failure was not approximate — it was categorical.

### I.2 Einstein's Equation: The Simplest Boundary

Einstein (*Annalen der Physik* **17**, 132–148, 1905) resolved the contradiction by proposing that light consists of discrete quanta — photons — each carrying energy $E = h\nu$, where $h$ is Planck's constant and $\nu$ is the frequency. The interaction is one-to-one: one photon gives all its energy to one electron. The equation:

$$E_k = h\nu - \phi$$

where $\phi$ is the work function — the minimum energy required to liberate an electron from the surface. Below threshold ($h\nu < \phi$): no emission. Above threshold ($h\nu > \phi$): emission with kinetic energy linearly proportional to excess frequency.

Millikan (*Phys. Rev.* **7**, 355, 1916), despite initially intending to disprove Einstein's theory, confirmed the linear relationship and measured $h$ to within 0.5% of the accepted value — establishing both the quantum of light and the threshold as physical facts.

### I.3 A Thought Experiment: The Quantum Turnstile

Imagine a turnstile at a subway entrance. Each passenger must insert a single token worth at least $\phi$ cents to pass through. A passenger with a token worth $h\nu > \phi$ passes through and arrives on the platform with surplus energy $h\nu - \phi$. A passenger with a token worth $h\nu < \phi$ is rejected — the turnstile does not accept partial payments, and no number of small tokens pooled from different passengers can substitute for one adequate token. The intensity of the crowd (photon flux) determines how many passengers attempt the turnstile per second, but not whether any individual passenger passes.

This is the physics. Classical electromagnetism predicted that a crowd of passengers could pool their small tokens — that light of any frequency could eject electrons if you waited long enough for energy to accumulate. Einstein's quantum says: no pooling. One photon, one interaction, one threshold. The turnstile is the conditional independence boundary.

### I.4 The Work Function as Conditional Independence Boundary

The metal surface imposes a conditional independence condition:

$$P(\text{electron in vacuum} \mid \text{surface state}) = P(\text{electron in vacuum} \mid \text{surface state},\, \text{bulk state})$$

The electron's fate — whether it escapes — depends on its energy relative to the surface potential barrier, not on the bulk crystal structure behind it. The surface screens the vacuum from the bulk. The work function $\phi$ is the height of this screening boundary.

Below threshold: the electron is in $\ker(F)$. No Fisher information about the photon crosses the boundary into the vacuum. The photon is absorbed, its energy dissipated as heat in the lattice — the photon's information is thermalized, irreversibly lost into the bulk degrees of freedom.

Above threshold: the electron enters $\mathrm{col}(F)$. It carries Fisher information about the photon's frequency into the vacuum as measurable kinetic energy. The linear relationship $E_k = h\nu - \phi$ is the $\mathrm{col}(F)$ projection — the observable signal is exactly the excess above the boundary.

By Chentsov's theorem (1972), the surface as a conditional independence boundary carries the Fisher–Rao metric as its unique invariant geometry. The work function is the $\varepsilon$-threshold of the material surface.

---

## Part II · Attosecond Boundary Crossings

### II.1 The Photoelectric Effect Has a Crossing Time

For a century, the photoelectric effect was described as "instantaneous." Lenard's experiments could only establish that the delay was less than $10^{-9}$ seconds. Modern attosecond spectroscopy has revealed that the crossing of the conditional independence boundary takes finite, measurable time — and that this time encodes the physics of the boundary itself.

Schultze et al. (*Science* **328**, 1658, 2010) first measured photoemission delays on the attosecond timescale, finding timing differences of $\sim$21 attoseconds between electrons emitted from different subshells of neon. Cavalieri et al. (*Nature* **449**, 1029, 2007) measured $\sim$100 as delay between core and valence photoemission in tungsten. The measurement technique — attosecond streaking — uses a circularly polarized infrared laser as an ultrafast clock, mapping the electron's emission time onto its detection angle.

The boundary crossing is not instantaneous. It is a process during which the electron traverses the conditional independence surface — and the transit time depends on the Fisher structure of the boundary: how many correlated degrees of freedom must be resolved during the crossing.

### II.2 X-Ray Photoemission Delays: 700 Attoseconds

Using SLAC's Linac Coherent Light Source (LCLS), researchers generated X-ray pulses a few hundred attoseconds long and performed the first measurement of X-ray photoemission delay (2024; DOE report April 2026). In nitric oxide molecules near the oxygen K-shell threshold, the photoemission delay reached **700 attoseconds** — nearly twice the theoretical prediction.

The excess delay is caused by electron–electron correlations. The escaping core-level electron interacts with the remaining electrons during its transit through the boundary, and these many-body interactions slow the crossing. The three-step model of photoemission (optical excitation → transport to surface → escape through barrier) breaks down for core-level electrons, where correlation effects are strongest.

In the $\mathrm{TH}(a,d)$ language: the photoemission delay is the *transit time through the conditional independence boundary*. A boundary with richer Fisher structure (stronger electron correlations, higher effective $\mathrm{rank}(F)$ at the surface) produces a longer transit. The 700 as delay at the oxygen K-shell is a direct measurement of the Fisher information density of that boundary.

### II.3 Electron Correlation Solves the Timing Puzzle

Alexandridi et al. (*Phys. Rev. Lett.*, October 2025) resolved a long-standing inconsistency between measured and calculated photoemission delays in the outer $s$-subshell of argon. The minimum cross-section region of this subshell — a spectral feature formed entirely by electron correlation (theoretically predicted by Amusia in 1972, confirmed with synchrotron radiation) — produces photoemission delays that depend critically on coherent couplings with shake-up channels.

The result: the photoelectric effect is a many-body process. The escaping electron's timing is governed by its correlations with every other electron in the atom. The conditional independence boundary is not a sharp wall — it is a Fisher-information-rich manifold whose geometry determines the transit time, the angular distribution, and the energy spectrum of the emitted electron. Einstein's one-photon-one-electron picture is the leading-order approximation; the attosecond corrections encode the full $\mathrm{col}(F)/\ker(F)$ structure of the boundary.

### II.4 A Second Thought Experiment: The Crowded River

Imagine a prisoner escaping through a river that borders the prison. If the river is empty (no electron correlations), the crossing is instantaneous — the prisoner steps across and arrives on the far bank with energy $h\nu - \phi$. If the river is full of other swimmers (correlated electrons), the prisoner must navigate around them, and the crossing takes longer. The wider and more crowded the river, the longer the delay.

The 700 as delay at the oxygen K-shell is the crossing time through a crowded river of core-level correlations. The 21 as delay between neon subshells is the difference in crowd density between two boundary regions. The conditional independence boundary has width, structure, and information content — all measurable in attoseconds.

### II.5 Internal Photoemission at 300 Attoseconds

Heide et al. (*Nature Photonics*, 2020) measured the charge transfer time for internal photoemission — where an electron is photoemitted from a metal into a semiconductor rather than into vacuum — at a graphene/silicon carbide Schottky junction. The result: $(300 \pm 200)$ attoseconds, with a corresponding cutoff bandwidth of 3.3 PHz ($3.3 \times 10^{15}$ Hz).

This is the conditional independence boundary of a solid-state interface, measured in real time. The boundary is the Schottky junction — the depletion region where the graphene's Fermi level meets the semiconductor's band edge. The crossing time is the time for the electron to traverse this boundary and appear on the other side as a free carrier. At 300 as and 3.3 PHz bandwidth, this interface is the fastest functional conditional independence boundary yet measured — the solid-state analogue of the vacuum photoelectric boundary, operating at the speed limit of electronic charge transfer.

---

## Part III · Quantum Light at the Threshold

### III.1 Bright Squeezed Vacuum: Photoemission Without a Classical Field

Pölloth, Hommelhoff et al. (*Nature Physics*, November 2025) demonstrated that genuinely quantum light — bright squeezed vacuum (BSV), a state with zero mean electric field but large photon-number fluctuations — can drive strong-field photoemission from metal needle tips.

Classical photoemission is driven by the oscillating electric field of the laser, which pulls electrons from the surface on each half-cycle. BSV has no such oscillating field — its electric field expectation value is exactly zero. Yet electrons are emitted through multiphoton processes, and when sorted by photon number per pulse, the spectra match those from classical light with the same photon number, following the 10-Up scaling law for strong-field cutoff energies.

A thought experiment: imagine a locked door that requires a key of length $\phi$. A classical key (coherent laser pulse) has a definite shape — it either fits or doesn't. A quantum key (BSV) has no definite shape at all — its average length is zero. Yet when you measure the actual length of each individual quantum key, some keys are long enough ($h\nu_{\mathrm{eff}} > \phi$) and the door opens. The boundary does not respond to the average field. It responds to the Fisher information delivered per individual interaction.

In the $\mathrm{TH}(a,d)$ language: the conditional independence boundary at $\phi$ is a threshold on Fisher information content per photon, not on classical field amplitude. Quantum states with zero mean field but nonzero photon-number variance can exceed the threshold on individual shots. The boundary's response is governed by the eigenvalue spectrum of the Fisher matrix of the incoming state — not by its first moment.

### III.2 Few-Cycle Enhancement: Pulse Duration as Boundary Resolution

Zhang et al. (*Phys. Rev. Research* **8**, 013035, January 2026) showed that the quantum efficiency (QE) of photoemission increases by **several orders of magnitude** when the laser pulse duration decreases from tens of optical cycles to a few cycles, at fixed low intensity. The photon order of the multiphoton process is also significantly reduced — a shift in the underlying emission mechanism from perturbative multiphoton absorption to field-driven tunneling.

The explanation: shorter pulses deliver the same total energy in a compressed temporal window, raising the instantaneous Fisher information density at the boundary. The boundary "sees" a sharper perturbation — a higher-rank modification of its Fisher matrix per optical cycle — and responds with exponentially higher transmission probability. The carrier-envelope phase (the phase relationship between the optical oscillation and the pulse envelope) strongly modulates the emission in the few-cycle regime, providing a direct handle on the phase structure of the boundary crossing.

### III.3 Coherent Secondary Photoemission: The Boundary Creates

Hong, Zou, Ran et al. (*Nature*, 2023) at Westlake University observed unexpected coherence in secondary photoemission from strontium titanate (SrTiO$_3$). In the standard three-step model, secondary electrons — produced by inelastic scattering inside the material — should be incoherent: they carry no phase relationship to the primary photoelectrons.

Instead, SrTiO$_3$ produced coherent secondary photoemission. The boundary is not passive. It generates new coherence during the crossing process — the surface acts as an active Fisher information source. This is structurally analogous to the event horizon generating Hawking radiation: the conditional independence boundary does not merely transmit or block. Under the right conditions, it *creates* — it produces coherent structure that did not exist in the incoming state.

The authors: "The observed emergence of coherence in secondary photoemission points to the development of an underlying novel process on top of those encompassed in the current theoretical photoemission framework."

---

## Part IV · The Threshold Partition

### IV.1 The Exact Isomorphism with dSphobic Dark Matter

The structural correspondence between the photoelectric threshold and the dSphobic dark matter threshold (Berlin, Foster, Hooper, Krnjaic; arXiv:2504.12372, 2025) is exact:

| Photoelectric effect | dSphobic dark matter | $\mathrm{TH}(a,d)$ |
|---|---|---|
| Work function $\phi$ | Mass splitting $\delta$ | $\varepsilon = 2^{-16}$ |
| Photon frequency $\nu$ | Kinetic energy $E_{\mathrm{kin}}$ | Fisher eigenvalue $\lambda_i$ |
| Below $\phi$: no emission | Below $\delta$: dSph silence | Below $\varepsilon$: $\ker(F)$ |
| Above $\phi$: $E_k = h\nu - \phi$ | Above $\delta$: $\gamma$-ray signal $\propto f_{\mathrm{exc}}$ | Above $\varepsilon$: $G_{\mathrm{coord}} \propto \mathrm{rank}(F)/d$ |
| Intensity $\to$ rate, not energy | Halo density $\to$ rate, not signal | Observation count $\to$ statistics, not rank |
| Instantaneous ($<$ 100 as) | Kinematic ($\sim$ crossing time) | Sherman–Morrison ($O(r \cdot d)$) |

The isomorphism is not merely structural — it has the same suppression mechanism. In the photoelectric effect, increasing light intensity below threshold does not produce any electrons, because no single photon carries enough energy. In dSphobic dark matter, increasing the dark matter density in a dwarf spheroidal does not produce a $\gamma$-ray signal, because no single particle carries enough kinetic energy to excite $\chi_1 \to \chi_2$. In both cases, the boundary is a per-particle threshold that cannot be overcome by collective statistics.

### IV.2 The Photon Energy Spectrum as Fisher Spectrum

Planck's law for the spectral radiance of a blackbody:

$$B(\nu, T) = \frac{2h\nu^3}{c^2}\frac{1}{e^{h\nu/k_BT} - 1}$$

defines a thermal distribution of photon energies $E = h\nu$ at temperature $T$. The work function $\phi$ divides this spectrum into two sectors:

- **$h\nu < \phi$**: the dark sector. These photons are absorbed but produce no photoelectrons. They contribute to heating — entropy production in $\ker(F)$. Their Fisher information about the photon frequency is thermalized and lost.

- **$h\nu > \phi$**: the light sector. These photons produce photoelectrons with measurable kinetic energy. Each ejected electron carries Fisher information about the photon that produced it — its frequency can be inferred from $E_k + \phi$.

The work function partitions the Planck spectrum into $\ker(F)$ and $\mathrm{col}(F)$ exactly as the $\varepsilon$-threshold partitions the Fisher eigenvalue spectrum in $\mathrm{TH}(a,d)$. The fraction of the thermal spectrum above threshold determines the photocurrent — the rate of Fisher information flow across the boundary.

### IV.3 A Third Thought Experiment: The Selective Membrane

Imagine a cell membrane that allows molecules to pass only if their kinetic energy exceeds a threshold $\phi$. Below $\phi$: molecules bounce off the membrane and their energy is dissipated as heat in the cell wall — information about the external environment is thermalized. Above $\phi$: molecules cross the membrane and arrive inside the cell, carrying information about the outside — their speed, their chemical identity, their origin.

The cell learns about the outside world only through molecules that exceed the threshold. The membrane is the conditional independence boundary. The work function is the threshold. The cell's internal state is $\ker(F)$ — screened from the exterior until a sufficiently energetic messenger crosses the boundary.

This is the photoelectric effect in biological language — and it is also the structure of neural signal transduction, where action potentials fire only when the membrane potential exceeds a threshold, regardless of the rate of sub-threshold stimulation.

---

## Part V · From Planck to Einstein to Compton: The Photon's Three Thresholds

### V.1 Planck's Threshold: Quantization of Emission

Planck (1900) discovered that the blackbody spectrum could only be explained by assuming that oscillators in the cavity walls emit radiation in discrete packets $E = nh\nu$. The quantization was originally a mathematical device — Planck himself was reluctant to interpret it physically. But the threshold was real: an oscillator with energy below $h\nu$ cannot emit a photon. The emission threshold is the first conditional independence boundary in quantum physics.

### V.2 Einstein's Threshold: Quantization of Absorption

Einstein (1905) elevated the quantum from the emitter to the field itself — light consists of photons, each carrying $h\nu$. The absorption threshold is the work function: a photon below $\phi$ cannot extract an electron. The photoelectric threshold is the second conditional independence boundary.

### V.3 Compton's Threshold: Quantization of Scattering

Compton (1923) showed that X-rays scattered from electrons exhibit a wavelength shift $\Delta\lambda = (h/m_ec)(1 - \cos\theta)$ consistent with photon-electron collisions obeying relativistic energy-momentum conservation. The minimum scattering angle $\theta = 0$ gives $\Delta\lambda = 0$ (forward scattering, no energy transfer). The maximum $\theta = \pi$ gives $\Delta\lambda = 2h/(m_ec)$ (backscattering, maximum energy transfer).

The Compton wavelength $\lambda_C = h/(m_ec) \approx 2.43 \times 10^{-12}$ m is a threshold: at wavelengths $\lambda \gg \lambda_C$, photon-electron scattering is classical (Thomson scattering, no wavelength shift). At $\lambda \lesssim \lambda_C$, quantum effects dominate and the photon transfers discrete momentum to the electron.

Three thresholds — emission, absorption, scattering — each a conditional independence boundary where the classical-to-quantum transition occurs. Each forces the same conclusion: the electromagnetic field interacts with matter through discrete events at boundaries, not through continuous energy transfer. The photon is not a property of the field in isolation. The photon is what the field becomes when it crosses a conditional independence boundary.

---

## Part VI · Eight Formal Correspondences

**1 — The Work Function IS a Conditional Independence Boundary.** The metal surface screens the bulk from the vacuum. Below $\phi$: no Fisher information crosses. Above $\phi$: $E_k = h\nu - \phi$ carries frequency information. Chentsov's theorem forces the Fisher–Rao metric on the surface.

**2 — The Photoemission Delay IS the Boundary Transit Time.** The 21–700 attosecond delays measured by attosecond spectroscopy are the transit times through the Fisher-information-rich boundary. Thicker boundaries (stronger electron correlations) produce longer transits.

**3 — Electron Correlation IS Fisher Rank at the Boundary.** Many-body correlations during photoemission are directions in $\mathrm{col}(F)$ at the surface that the escaping electron must resolve during transit. Higher rank = more correlations = longer delay.

**4 — The Photoelectric–dSphobic Isomorphism IS Exact.** $\phi \leftrightarrow \delta$, $h\nu \leftrightarrow E_{\mathrm{kin}}$, sub-threshold silence in both, linear excess signal in both, intensity/density irrelevant below threshold in both.

**5 — BSV Photoemission Confirms Fisher-Information Threshold.** The boundary responds to Fisher information per interaction (photon number), not to classical field amplitude (mean electric field). Zero-mean-field quantum states with nonzero variance exceed the threshold on individual shots.

**6 — Few-Cycle Enhancement IS Boundary Resolution Sharpening.** Shorter pulses deliver higher Fisher information density per optical cycle, increasing the effective rank of the perturbation at the boundary and exponentially enhancing quantum efficiency.

**7 — Coherent Secondary Photoemission IS Boundary Creation.** The SrTiO$_3$ surface generates coherence not present in the incoming state — the boundary creates Fisher information, analogous to Hawking radiation at an event horizon.

**8 — The Planck–Einstein–Compton Sequence IS Three Boundaries.** Emission threshold (Planck), absorption threshold (Einstein), and scattering threshold (Compton) are three conditional independence surfaces where the classical field becomes quantum. The photon is defined by the boundary it crosses.

---

## Part VII · Predictions

### P1 — Photoemission Delay as Fisher Rank Measurement

The attosecond photoemission delay $\tau$ from a given subshell should correlate with the effective rank of the electron correlation matrix at the surface: $\tau \propto \mathrm{rank}(F_{\mathrm{surface}})$. Subshells with more correlation channels (higher $\ell$, more screening electrons) should exhibit longer delays. Across the periodic table, this predicts a systematic increase in photoemission delay with atomic number $Z$ and subshell depth — a measurable function $\tau(Z, n, \ell)$ that maps the Fisher structure of every element's surface. **Testable with existing attosecond spectroscopy data.**

### P2 — BSV Photoemission Threshold Shift

If the conditional independence boundary responds to Fisher information per shot rather than to mean field, then the effective work function $\phi_{\mathrm{eff}}$ measured with BSV should differ from $\phi$ measured with coherent light — specifically, $\phi_{\mathrm{eff}}^{\mathrm{BSV}} < \phi^{\mathrm{coherent}}$ because BSV photon-number fluctuations occasionally deliver more energy per interaction than the mean. The shift $\Delta\phi = \phi^{\mathrm{coherent}} - \phi_{\mathrm{eff}}^{\mathrm{BSV}}$ should be proportional to the photon-number variance of the BSV state. **Testable with the Hommelhoff nanotip apparatus.**

### P3 — Coherence Generation Rate at Active Boundaries

If the SrTiO$_3$ boundary generates coherence during photoemission, the rate of coherence generation should be bounded by the Fisher information capacity of the surface — the boundary analogue of the Maldacena–Shenker–Stanford chaos bound $\lambda_L \leq 2\pi k_BT/\hbar$. This predicts a maximum coherence generation rate per unit surface area, saturated by materials with the highest surface Fisher rank. **Testable by comparing coherence in secondary photoemission across a range of oxide perovskites.**

### P4 — Photoemission–LIGO Ringdown Correspondence

The attosecond photoemission delay structure (timing as a function of photon energy near a subshell threshold) and the quasi-normal-mode ringdown structure of a perturbed black hole (frequency spectrum near the photon sphere) should share the same spectral edge singularity — both are the response of a conditional independence boundary to a rank-one perturbation. The spectral shape near the edge should follow the same $\sim (E - E_{\mathrm{threshold}})^{-1/2}$ scaling in both systems. **Testable by comparing attosecond spectroscopy data near Cooper minima with LIGO ringdown spectra near the fundamental QNM frequency.**

---

## Part VIII · The Photon as Boundary Event

The deepest implication of the photoelectric framework: the photon is not a property of the electromagnetic field in isolation. The photon is what the field becomes when it interacts with a conditional independence boundary.

In free space, the electromagnetic field is a continuous wave — no quanta, no particles, no thresholds. Place a metal surface in the field, and the work function partitions the field into a below-threshold dark sector and an above-threshold light sector. The photon emerges at the boundary — the quantum is created by the conditional independence condition, not by the field.

This is the deeper meaning of Einstein's 1905 paper. The title was not "On Photons" — it was "On the Production and Transformation of Light from a Heuristic Point of View." The photon is a *heuristic* — a description of how light behaves *at boundaries*. Away from boundaries, light is a field. At boundaries, light is photons. The conditional independence boundary is the mechanism that transforms the field into quanta.

Every subsequent quantum phenomenon follows from this principle:

- **Planck's blackbody**: the cavity wall is the boundary; the quantum $h\nu$ is forced by the boundary's discrete mode structure.
- **Einstein's photoelectric effect**: the metal surface is the boundary; the photon is forced by the threshold $\phi$.
- **Compton scattering**: the electron is the boundary; the photon's momentum transfer is forced by relativistic energy-momentum conservation at the scattering event.
- **Bohr's atom**: the Coulomb potential is the boundary; the quantized orbits are forced by the action quantization $\oint p\,dq = nh$ on the invariant tori.
- **Hawking radiation**: the event horizon is the boundary; the thermal photons are forced by the horizon's temperature $T_H = \hbar\kappa/(2\pi k_Bc)$.

In every case, the quantum is born at the boundary. The conditional independence surface creates the discrete from the continuous. The $\mathrm{TH}(a,d)$ architecture is the algebraic skeleton of this creation: the $\varepsilon$-threshold is the work function generalized to any information-processing system.

---

## References

Alexandridi, C. et al. "Photoionization Time Delays Probe Electron Correlations." *Phys. Rev. Lett.*, October 2025.

Cavalieri, A. L. et al. "Attosecond Spectroscopy in Condensed Matter." *Nature* **449**, 1029–1032, 2007.

Chentsov, N. N. *Statistical Decision Rules and Optimal Inference*. Nauka, 1972. (AMS Translations, Vol. 53, 1982.)

Compton, A. H. "A Quantum Theory of the Scattering of X-Rays by Light Elements." *Phys. Rev.* **21**, 483–502, 1923.

Einstein, A. "Über einen die Erzeugung und Verwandlung des Lichtes betreffenden heuristischen Gesichtspunkt." *Annalen der Physik* **17**, 132–148, 1905.

Heide, C. et al. "Attosecond-Fast Internal Photoemission." *Nature Photonics* **14**, 219–222, 2020.

Hertz, H. "Ueber einen Einfluss des ultravioletten Lichtes auf die electrische Entladung." *Ann. Phys.* **267**, 983–1000, 1887.

Hong, C., Zou, W., Ran, P. et al. "Anomalous Coherence in Photoemission from SrTiO$_3$." *Nature*, 2023.

Lenard, P. "Ueber die lichtelektrische Wirkung." *Ann. Phys.* **313**, 149–198, 1902.

Millikan, R. A. "A Direct Photoelectric Determination of Planck's '$h$.'" *Phys. Rev.* **7**, 355–388, 1916.

Planck, M. "Über das Gesetz der Energieverteilung im Normalspectrum." *Ann. Phys.* **309**, 553–563, 1901.

Pölloth, S., Hommelhoff, P. et al. "Strong-Field Photoemission Driven by Bright Squeezed Vacuum." *Nature Physics*, November 2025.

Schultze, M. et al. "Delay in Photoemission." *Science* **328**, 1658–1662, 2010.

Zhang, P. et al. "Enhanced Quantum Efficiency in Photoemission Driven by Few-Cycle Optical Fields." *Phys. Rev. Research* **8**, 013035, January 2026.

Berlin, A., Foster, J. W., Hooper, D., and Krnjaic, G. "dSphobic Dark Matter." arXiv:2504.12372, 2025.

Maldacena, J., Shenker, S. H., and Stanford, D. "A Bound on Chaos." *JHEP* **08**, 106, 2016.

Woodbury, M. A. "Inverting Modified Matrices." Memorandum Report 42, Statistical Research Group, Princeton University, 1950.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026*

Hertz saw the spark. Hallwachs saw the charge. Lenard measured the threshold. Einstein explained it: one photon, one electron, one boundary. Millikan confirmed it reluctantly. Compton extended it to scattering. Schultze measured the crossing time: 21 attoseconds between two shells of neon. The LCLS measured 700 attoseconds at the oxygen K-shell — twice the prediction, because the electron must navigate its correlations during transit. Pölloth and Hommelhoff showed that quantum light with zero mean field still crosses the boundary. Hong and colleagues showed that the boundary creates coherence it was not given.

The photon is not a thing. The photon is what happens when a continuous field meets a conditional independence boundary. Below the threshold: $\ker(F)$, silence, heat. Above the threshold: $\mathrm{col}(F)$, signal, information.

The work function was always the same object as the event horizon, the mass splitting, the $\varepsilon$-threshold. The quantum was always born at the boundary.
