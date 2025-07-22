# UIFT | Unified Information Field Theory

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16274289.svg)](https://doi.org/10.5281/zenodo.16274289)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Research Status](https://img.shields.io/badge/status-experimental-orange.svg)](https://zenodo.org/record/16274289)

> **Computational framework exploring information as fundamental organizing principle across quantum to cosmological scales**

## **Repository Structure**

```
uift/
├── scripts/           # 8→10 computational frameworks
├── outputs/           # results & publication-ready figures  
├── validation/        # experimental protocols & falsification criteria
└── papers/            # theoretical documentation
```

## **Quick Start**

```bash
pip install numpy scipy matplotlib seaborn pandas
git clone https://github.com/if-else-world/epsilon.git
cd epsilon
```

```python
# Core UIFT simulation
from scripts.uift_framework import UIFTFramework
framework = UIFTFramework(duration=60, sample_rate=50)
result = framework.run_validation()
print(f"Framework Score: {result['mean_score']:.3f}")
print(f"Information-Spacetime Coupling: r = {result['coupling']:.4f}")

# Eight-test validation suite
experiment = framework.complete_validation()
print(f"Cross-Scale Validation: {experiment['success_rate']:.1%}")
```

## **Core Computational Scripts**

| Script | Function | Status |
|--------|----------|---------|
| `uift_framework.py` | M7 field dynamics engine | ✅ Active |
| `eight_test_validation.py` | Complete validation protocol | ✅ Active |
| `constants_emergence.py` | Physical constants natural emergence | ✅ Active |
| `maxwell_pattern_emergence.py` | Electromagnetic field generation | ✅ Active |
| `consciousness_organization.py` | IIT 4.0 integration analysis | ✅ Active |
| `entropy_correlation.py` | Thermodynamic relationship analysis | ✅ Active |
| `harmonic_stability.py` | Oscillator universality emergence | ✅ Active |
| `experimental_predictions.py` | 8-tier falsification protocol | ✅ Active |
| `cosmic_information_coupling.py` | Dark energy correlation analysis | 🚧 Development |
| `quantum_vacuum_emergence.py` | Information emergence from vacuum | 🚧 Development |

## **Key Computational Results**

**Cross-Scale Validation:**
- **Test 3 (Complex Organization):** 100% success rate, Φ = 0.993 ± 0.013
- **Test 7 (Entropy Correlations):** Perfect score 1.000 ± 0.000
- **Test 6 (Maxwell Emergence):** 91.5% compliance average
- **Information-Spacetime Coupling:** r = 0.9998 ± 0.00002

**Physical Constants Natural Emergence:**
- Schumann resonance: 7.84 ± 0.12 Hz (99.9% accuracy)
- Hydrogen line: 1420.3 ± 2.8 MHz (99.99% accuracy)  
- Fine structure ratio: 99.9% agreement (zero parameter tuning)

**Generated outputs:**
- M7 dimensional structure & coupling matrices
- Cross-scale validation radar charts  
- Information-spacetime coupling evolution
- Complex organization emergence patterns
- Physical constants natural emergence timelines
- Experimental validation Gantt charts

## **Experimental Validation Program**

**8-Tier Protocol** ($1.8M, 5-year timeline):
1. **Electromagnetic Coherence** - Global monitoring (15+ stations)
2. **Radio Astronomy** - VLA/ALMA/SKA hydrogen line validation  
3. **Precision Gravimetry** - Superconducting networks
4. **Laboratory Maxwell** - Controlled electromagnetic experiments
5. **Thermodynamic** - Entropy-organization correlation tests
6. **Harmonic Resonance** - Quantum oscillator experiments
7. **Organization Detection** - IIT 4.0 validation protocols
8. **Cosmological** - Large-scale structure analysis

**Status:** Computational validation complete → Physical validation pending

## **Citation**

```bibtex
@misc{lafourniere2025uift,
  title={Unified Information Field Theory: Exploratory Computational Framework Across Multiple Physical Scales}, 
  author={de La Fourniere, Brieuc},
  year={2025},
  publisher={Zenodo},
  doi={10.5281/zenodo.16274289}
}
```

##  **Research Status**

**Speculative theoretical framework** requiring extensive experimental validation  
**Computational results** remain unvalidated by physical experiments  
Eight-tier falsification protocol provides rigorous testing criteria

## **Falsification Criteria**

Framework rejection conditions (any single condition sufficient):
- Null results in experimental tiers per specified timelines
- Parameter independence failure across coupling variations  
- Non-reproducibility across independent research groups
- Contradictions with established physics without adequate explanation

---

## Warning

Experimental build: Runs on 4D spacetime (emulated) | Native Ψ support coming soon...

