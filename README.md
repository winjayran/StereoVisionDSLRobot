# StereoVisionDSLRobot

This README gives a one-sentence English description for each project file currently included in the repository, excluding `.git` metadata.

## Demo Video

<video controls width="100%">
  <source src="result/performance.mp4" type="video/mp4">
  Your Markdown viewer does not support inline video playback, so open `result/performance.mp4` directly.
</video>

If the video does not render inline, open [result/performance.mp4](result/performance.mp4) directly.

## File Guide

| File | Description |
| --- | --- |
| `LICENSE` | This file contains the license terms that define how the repository can be used, modified, and shared. |
| `README.md` | This file provides a short overview of the repository and a one-line explanation for each project file. |
| `report/finalReport.pdf` | This PDF is the final project report summarizing the method, experiments, results, and conclusions. |
| `report/final_report.tex` | This LaTeX source file defines the final project report for the stereo-vision closed-loop manipulation system. |
| `report/presentation.pdf` | This PDF contains the final presentation slides summarizing the project design, experiments, and results. |
| `report/presentation.tex` | This LaTeX source file defines the final presentation slides used for the project demo and summary. |
| `report/proposal.pdf` | This PDF is the project proposal describing the problem, motivation, planned method, and evaluation idea. |
| `report/proposal.tex` | This LaTeX source file defines the written project proposal for the modular language-guided manipulation approach. |
| `result/Idefics3_fail.mp4` | This video records a failure case from the Idefics3-based stereo cube-grabbing experiment. |
| `result/milkBottleFailed.mp4` | This video records a failure case from the bottle-grabbing experiment. |
| `result/performance.mp4` | This video demonstrates the overall manipulation performance of the main stereo-vision robot pipeline. |
| `result/smolVLM2.2B_fail.mp4` | This video records a failure case from the SmolVLM2-based stereo cube-grabbing experiment. |
| `src_notebook/finalBottleGrabbing.ipynb` | This notebook implements the final stereo bottle-grabbing pipeline with Qwen3-VL planning, 3D triangulation, and Robosuite execution. |
| `src_notebook/finalCubeGrabbing.ipynb` | This notebook implements the main final stereo cube-grabbing pipeline with Qwen3-VL, stereo triangulation, and robot action execution. |
| `src_notebook/finalCubeGrabbing-idefics3.ipynb` | This notebook is a final stereo cube-grabbing variant that uses Idefics3 instead of Qwen3-VL for visual planning and action generation. |
| `src_notebook/finalCubeGrabbing-llavaonevision.ipynb` | This notebook is a final stereo cube-grabbing variant that uses LLaVA-OneVision as the vision-language planner. |
| `src_notebook/finalCubeGrabbing-smolvlm2.ipynb` | This notebook is a final stereo cube-grabbing variant that uses SmolVLM2 as a lighter vision-language planner. |
| `src_notebook/monocularVisionOrigin.ipynb` | This notebook is the earlier monocular baseline that maps natural language to DSL actions and grounds targets from a single camera view. |
| `src_notebook/rl_test.ipynb` | This notebook explores GRPO-style LoRA reinforcement learning for Qwen3-VL inside a Robosuite and MuJoCo training loop. |
| `src_notebook/twoViewsGrabbing.ipynb` | This notebook is an earlier two-view grasping prototype that combines Qwen3-VL perception and planning with 3D projection. |
