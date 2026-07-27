# Signal Processing — Audible Tone Generation in MATLAB

A Digital Signal Processing mini-project on **generating audible tones in
MATLAB** by synthesizing sinusoidal waveforms, then sequencing them to play a
recognizable melody ("Happy Birthday").

## Overview

Sound is generated as discrete samples of `y(t) = sin(2·pi·f·t)`, where each
musical note maps to a frequency (e.g. A4 = 440 Hz). By defining a sampling
frequency, building a time vector, and using MATLAB's `sound()` function, the
project demonstrates core DSP concepts: sampling, waveform generation,
harmonic synthesis, amplitude/phase control, and time sequencing.

## Objectives

- Understand sound generation from sinusoidal signals
- Implement a MATLAB program that generates musical tones and melodies
- Study how frequency, duration and amplitude shape the resulting tone

## Contents

- `DSP_TA.pdf` — full project report (theory, flowchart, MATLAB code, results)

## Course

Digital Signal Processing (ECT 5002), 5th Semester B.Tech —
Ramdeobaba College of Engineering & Management, Nagpur.

## Team

Akul Kute, Anand Gupta, Dev Singh, Dhairya Wegad.
