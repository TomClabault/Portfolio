# - M2-
## \[Individuel\] (En cours) Moteur de rendu par path tracing (Monte Carlo) - C++, SYCL
Fonctionnalités implémentées:
- Éclairage direct
- Éclairage indirect (nombre de rebonds arbitraire)
- Modèle de matière à micro facettes (BRDF de Cook Torrance): Métallique et rugosité
- Échantillonnage préférentiel de la BRDF de Cook Torrance
- Environment map HDR
- Tone mapping HDR (gamma et exposition)
- BVH (hiérarchie de volumes englobants) basée sur un octree + volumes englobants à 7 plans
- Intégration d'Intel® Open Image Denoise

![démonstration SDF](README_data/img/PBRT_Dragon.jpg)
## \[Personnel\] (En cours) Interpréteur 8086 - C++
Projet personnel en lien avec le cours en ligne "Performance Aware Programming" de Casey Muratori: https://www.computerenhance.com/

Fonctionnalités implémentées:
- Décodage de l'instruction MOV
## \[Individuel\] (Terminé) Moteur de rendu par rastérisation - C++, OpenGL
Moteur de rendu temps réel écrit en C++ et utilisant OpenGL.

Fonctionnalités implémentées:
- Intégration de ImGui
- Frustum culling
- Shadow mapping (Percentage closer filtering)
- Modèle de matière à micro facettes (BRDF de Cook Torrance): Métallique et rugosité
- Textures : Diffuse, métallique, rugosité
- Normal mapping
- Irradiance Mapping (pré calcul de la composante diffuse de l'éclairage à partir d'une environment map)
- Skysphere & skybox
- Tone mapping HDR (gamma et exposition)
## \[Individuel\] (Terminé) Modélisation géométrique (SDF, surfaces de Bézier et déformations de maillages) - C++, Qt6
Modélisation géométrique par SDF (fonctions de distance signée), surfaces de Bézier, surfaces de révolution + fonctionnalités de déformation

Fonctionnalités implémentées:

- Fonctions de distance signée (SDF)
- Opérateur binaires entre SDF (union, union lisse, intersection, différence, ...)
- Algorithme de ray marching pour le rendu des SDF

![démonstration SDF](README_data/img/SDF_to_the_right.jpg)


- Génération de points sur une surface de Bézier + maillage de la surface
- Déformation locale d'un maillage
![démonstration Bézier](README_data/img/Bezier.jpg)


- Surface de révolution utilisant une courbe de Bézier comme profil de révolution
- Torsion d'un maillage
![démonstration Bézier](README_data/img/torsion.jpg)
## \[Individuel\] (Terminé) Raffinement de maillage 2D (triangulation de Delaunay) - C++
Projet de géométrie algorithmique sur des maillages triangulés 2D.

Fonctionnalités implémentées:
- Insertion d'un point à l'intérieur/extérieur d'un maillage et remaillage de la surface
- Algorithme de Lawson pour améliorer la qualité d'un maillage (triangulation de Delaunay)
- Algorithme de Rupert (triangulation de Delaunay contrainte)
![démonstration Bézier](README_data/img/demo_lawson.jpg)
# - M1 -

## \[Personnel\] (Terminé) Moteur de rendu par path tracing (Monte Carlo) - C++,  NVIDIA OptiX 7

## \[En groupe\] (Terminé) Moteur de rendu par ray tracing + rastérisation (hybrid) - C++,  Qt6
Fonctionnalités implémentées:

- Interface entièrement faite avec Qt6 C++
![démonstration Bézier](README_data/img/RT_M1_Interface1.png)
- Rendu par lancer de rayons
- Rendu par rastérisation
- Algorithme de clipping en clip space
- Rendu hybride (rastérisation pour la visibilité, lancer de rayons pour le shading)
- Ombres franches (lancer de rayons secondaires)
![ombres franches](README_data/img/hard_shadows.jpg)
- BVH (hiérarchie de volumes englobants) basée sur un octree + volumes englobants à 7 plans
- Réflexions floues (rugosité)
- Normal mapping
- Diffuse texture, roughness map, ambient occlusion map
- Parallax occlusion mapping
- Skysphere
![Démonstration normal mapping, parallax, réflexions floues, skysphere](README_data/img/sphere_rose.jpeg)
- Skybox
- Super Sampling Anti Aliasing
- Implémentation AVX2 (speedup x8) de Screen Space Ambient Occlusion (SSAO)
![Démonstration SSAO](README_data/img/ssao.jpg)

## \[En groupe\] (Terminé) Détection de contours (filtres de Sobel, Prewitt) et de lignes (transformée de Hough) C++, OpenCV
# - L3 -
## \[Personnel\] (Terminé) Filtre de Canny (détection de contours) - C, NVIDIA CUDA

## \[En groupe\] (Terminé) Moteur de rendu par ray tracing - Java, JavaFX

## \[En groupe\] (Terminé) Application de gestion de références bibliographiques - Java, JavaFX