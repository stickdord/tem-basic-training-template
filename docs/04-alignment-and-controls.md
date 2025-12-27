# Module 4: Alignment and Controls

## Introduction
This module covers the essential operations needed to obtain a sharp, high‑contrast TEM image. You will learn how to adjust focus, correct astigmatism (stigmation), select appropriate apertures, change magnification, and control the beam convergence/divergence. Mastery of these controls is key to producing publication‑quality micrographs.

## 1. Basic Alignment

### Condenser Lens Alignment
- **Purpose**: To center the electron beam on the optical axis and ensure uniform illumination.
- **Procedure**:
  1. Set the microscope to diffraction mode (or spot mode).
  2. Defocus the condenser lens until a shadow of the condenser aperture appears.
  3. Use the condenser alignment (beam shift) knobs to center the aperture shadow.
  4. Refocus the condenser lens to obtain a parallel beam.

### Gun Tilt / Gun Shift
- **Purpose**: Optimizes the beam intensity and coherence.
- **Typically performed** by experienced users or during routine maintenance; you may not need to adjust these daily.

## 2. Aperture Selection

### Condenser Aperture
- **Location**: Below the condenser lens(es).
- **Effect on imaging**:
  - **Smaller aperture** → reduces beam convergence, decreases beam current, improves coherence, reduces spherical aberration, and increases image contrast (at the cost of intensity).
  - **Larger aperture** → higher beam current, brighter image, but increased spherical aberration and reduced contrast.
- **Typical sizes**: 10 µm, 20 µm, 50 µm, 100 µm.
- **When to change**: For high‑resolution work, a small (e.g., 20 µm) aperture is preferred; for low‑magnification survey images, a larger aperture can be used for faster viewing.

### Objective Aperture
- **Location**: At the back‑focal plane of the objective lens.
- **Primary function**: Enhance amplitude contrast by blocking scattered electrons.
- **Aperture size and contrast**:
  - Smaller objective aperture → higher contrast (but darker image).
  - Larger objective aperture → lower contrast, more signal.
- **Choosing an aperture**:
  - For biological samples (low contrast), a small objective aperture (e.g., 20 µm) is often used.
  - For crystalline materials, an aperture may be omitted to allow diffraction patterns.
- **Insertion/removal**: Use the aperture selector knob while watching the image; you should see a sudden change in contrast when the aperture is correctly positioned.

### Selected‑Area (SA) Aperture
- **Used for** obtaining diffraction patterns from a specific small area of the sample.
- **Procedure**: Center the area of interest, insert the SA aperture, adjust its position to isolate the desired region, then switch to diffraction mode.

## 3. Focus and Stigmation

### Recognizing Defocus
- **Under‑focus**: Features appear surrounded by bright Fresnel fringes (especially at edges and holes).
- **Over‑focus**: Features are surrounded by dark fringes.
- **In‑focus**: Fresnel fringes disappear; the image appears “crisp” but may have lower contrast.

### Focusing Steps
1. **Find a suitable feature** (e.g., a hole in the carbon film, a sharp particle edge) at a moderate magnification (e.g., 50 000×).
2. **Sweep through focus** using the coarse/fine focus knobs or the focus track.
3. **Observe the Fresnel fringes** at the feature’s edge; adjust until the fringes are minimized (the “minimum contrast” condition).
4. **Fine‑tune** with the objective lens current (or autofocus if available).

### Correcting Astigmatism (Stigmation)
Astigmatism arises when the electromagnetic lens does not focus equally in all directions, causing directional smearing of the image.

#### Visual Cues for Astigmatism
- **Directional blurring**: The image appears sharp in one direction and blurred in the perpendicular direction.
- **Change with focus**: As you move through focus, the blur rotates by 90°.
- **“Figure‑of‑eight” pattern** in the power spectrum (FFT) of a thin amorphous region (e.g., carbon film).

#### Stigmation Correction Procedure
1. **Choose a thin amorphous region** (carbon film) at high magnification (e.g., 200 000×).
2. **Slightly under‑focus** to see Fresnel fringes.
3. **Use the stigmator controls** (usually two knobs: X‑ and Y‑stigmator, or magnitude/direction).
4. **Adjust one knob** while watching the image; the direction of blur should change.
5. **Alternate between the two knobs** until the image remains isotropic while changing focus (i.e., the blur does not rotate).
6. **Re‑focus** to the desired defocus.

Many modern TEMs include an **automatic stigmator** that can be activated after a quick manual pre‑alignment.

## 4. Changing Magnification
- **Control**: Magnification knob or digital selector.
- **Important**: Higher magnification reduces the field of view and increases beam damage risk.
- **Workflow**:
  1. Start at low magnification (e.g., 2 000×) to locate your region of interest.
  2. Gradually increase magnification as needed (10 000× → 50 000× → 200 000×).
  3. At each step, re‑center the feature, re‑focus, and check for astigmatism.

## 5. Beam Convergence and Divergence

### Condenser Lens 2 (C2) Control
- **C2 lens strength** determines the convergence angle of the beam at the specimen.
- **Smaller convergence** (more parallel beam) → better coherence for high‑resolution imaging and electron diffraction.
- **Larger convergence** → higher beam current, brighter image, but reduced coherence.

### How to Adjust
- **“Parallel” illumination**: Set C2 to a strong value (often labeled “spot size 3” or “small spot”) to produce a nearly parallel beam. This is ideal for high‑resolution TEM (HRTEM) and selected‑area diffraction.
- **“Convergent” illumination**: Weaken C2 (larger spot size) for brighter images at low magnification or for scanning‑TEM (STEM) imaging.

### Condenser Aperture Interaction
- The condenser aperture physically limits the maximum convergence angle.
- A smaller condenser aperture forces a smaller convergence angle, even if C2 is set to a large spot size.

## 6. Practical Workflow for a New Sample
1. **Insert sample** (Module 3) and let the column stabilize.
2. **Set spot size** to a medium value (e.g., spot size 2).
3. **Select condenser aperture** (e.g., 50 µm for survey).
4. **Navigate at low magnification** (∼ 2 000×) to find a region of interest.
5. **Increase magnification** to ∼ 20 000×.
6. **Adjust focus** using a hole or particle edge.
7. **Correct astigmatism** using a thin amorphous region.
8. **Insert objective aperture** if needed for contrast.
9. **Switch to a smaller condenser aperture** (e.g., 20 µm) for high‑resolution work.
10. **Final focus and stigmation** at the desired magnification.

## 7. Safety and Best Practices
- **Avoid excessive beam current** on sensitive samples to prevent radiation damage.
- **Do not leave the beam stationary** on one spot for extended periods; use beam blanking when not actively observing.
- **Keep apertures clean**; contamination on an aperture can cause asymmetric illumination or astigmatism.
- **Document your settings** (aperture sizes, spot size, magnification, defocus) for reproducibility.

## Practice Task
Under supervision, load a gold‑on‑carbon test grid. Practice focusing, correcting astigmatism, and inserting/removing the objective aperture. Acquire a series of images at different magnifications and with different condenser apertures to observe the changes in contrast and resolution.

---

**Next**: After you are comfortable with alignment and controls, proceed to [Module 5: Image Acquisition](../docs/05-image-acquisition.md).