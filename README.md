# Kedem-Cycle-0.45
Kedem-Cycle Ω. Geometric theory of fundamental interactions based on the hyperbolic 3-manifold kaleidocycle L8a21 from the public SnapPy catalog. From geometry: gauge groups, masses of 28 particles, 7 dark states, neutrinos, fundamental constants, cosmology, and much more. 0.057% for 28 particles; 7 dark states at 28–50 GeV; E_grav ≈ 2.97 GeV. 
 # Kedem-Cycle Ω

**Kedem-Cycle Ω: Geometric Theory of Fundamental Interactions Based on the Hyperbolic 3-Manifold Kaleidocycle L8a21**

What if our Universe is not simply a system described by mathematics, but a concrete geometric object from the publicly available SnapPy catalog?

The Kedem-Cycle Ω theory proposes that the physical Universe corresponds to a single geometric structure — the hyperbolic 3-manifold kaleidocycle L8a21. It is a closed chain of ten tetrahedra, capable of continuous rotation without deformation of its elements.

Although the theory is formulated in the language of hyperbolic manifolds, geometry itself is not its foundation.

The primary entity is information.

Geometry is only one of the forms of its manifestation.

In the context of the theory, information exists in three states:

- geometric — frozen and structured;
- physical — manifested as matter and interactions;
- living — accumulated, growing with time.

These three states are connected by a single cycle: geometry is projected into physics, physics accumulates as living information, and what is accumulated returns to geometry. But it does not return to the starting point: each return changes the geometry, so the cycle takes the form of a spiral.

## Results

- Gauge groups SU(3)×SU(2)×U(1) with a proof of A₆ → SU(3)
- Masses of leptons, quarks, mesons, and baryons — 28 particles in total — with an average deviation of 0.057%
- Seven dark matter candidates in the range 28–50 GeV with a unique doublet and a splitting of 31 MeV
- Neutrino masses and all three PMNS mixing angles
- The fine-structure constant
- The Planck mass and the gravitational constant
- The dark energy density and the baryon asymmetry of the Universe
- The age of the Universe and the Hubble constant
- The nucleon magnetic moments and the anomalous magnetic moment of the electron
- The thresholds of stellar evolution
- The law of three-dimensional turbulence
- Quantum gravity with an energy quantum E_grav ≈ 2.97 GeV
- The Born rule as a theorem
- Wavefunction collapse as an information projection Z → L8a21

## Falsifiable Predictions

The theory is falsifiable. It predicts:

- seven ψ-resonances in the range 28–50 GeV;
- the doublet ψ₃/ψ₄ with a splitting of 31 MeV;
- resonances at energies n × 2.97 GeV.

If these signals are not detected, the theory must be considered refuted.

## Structure

- `Kedem-Cycle-v18-EN.pdf` — monograph (English, v18)
- `Kedem-Cycle-v18-RU.pdf` — monograph (Russian, v18)
- `_Kedem_Cycle_Omega.pdf` — preprint on particle masses
- `Information-Transformation-Law.pdf` — Information Transformation Law
- `CITATION.cff` — citation metadata
- `LICENSE` — MIT License
- `code/` — Python code for verification

## How to run

```bash
pip install snappy numpy scipy
python code/main.py
```

## Example output

```bash
$ python main.py --verify

============================================================
ШАГ 1: ЗАГРУЗКА И ФАКТОРИЗАЦИЯ
============================================================
L8a21: V=10.1494160641, CS=0.250000, cusps=4, tets=10
L8a20: V=10.1494160641, cusps=3
Z:     V=20.2988321282, cusps=5

============================================================
ШАГ 3: p-ИНВАРИАНТЫ
============================================================
  p1 = 0.707431
  p2 = 0.546712
  p3 = 0.448432
  p4 = 0.447640
  p5 = 0.266572
  p6 = 0.244028
  p7 = 0.218111
Сумма 10 проекций: 3.0000000000

============================================================
ШАГ 4: Ψ-ТОКИ
============================================================
J_ψ = 2κ = 0.2122065908
ΣJ(K₆) = 15 × J = 3.183099
ΣJ(K₇) = 21 × J = 4.456338

============================================================
ШАГ 5: ФОРМУЛА ШЕННОНА
============================================================
S_D = 20.000000

============================================================
ШАГ 7: ПЛАНКОВСКИЙ СЕКТОР
============================================================
M_Planck = 1.2209e+19 ГэВ (откл. 0.0032%)

============================================================
ШАГ 8: МАССЫ 28 ЧАСТИЦ
============================================================
Частиц: 28
Среднее отклонение: 0.0571%

============================================================
ШАГ 9: ТЁМНАЯ МАТЕРИЯ
============================================================
  ψ1 = 28.0362 ГэВ
  ψ2 = 31.8920 ГэВ
  ψ3 = 35.2138 ГэВ
  ψ4 = 35.2450 ГэВ
  ψ5 = 45.6724 ГэВ
  ψ6 = 47.7355 ГэВ
  ψ7 = 50.4920 ГэВ
ΔM(ψ₃/ψ₄) = 31.1620 МэВ (цель: 31 МэВ, откл: 0.5227%)

============================================================
ШАГ 11: КОНСТАНТЫ
============================================================
1/α_em = 137.036000

============================================================
ИТОГ ПРОВЕРКИ
============================================================
  Ψ-токи: 4.4563
  S_D = 20.0000
  M_base = 28.0362 ГэВ
  M_Planck = 1.2209e+19 ГэВ
  28 частиц: 0.0571%
  m_ν = 0.0478 эВ
  1/α_em = 137.0360
  η_B = 5.8689e-10
  w = -0.8571
  E_grav = 2.9747 ГэВ
```

## Citation

If you use this work, please cite it as:

**Monograph:**
Belmasova, I. Yu. (2026). *Kedem-Cycle Ω: Geometric Theory of Fundamental Interactions Based on the Hyperbolic 3-Manifold Kaleidocycle L8a21* (Version 18). Zenodo. https://doi.org/10.5281/zenodo.20364677

**Particle Masses preprint:**
Belmasova, I. Yu. (2026). *Particle Masses from the Geometry of the Hyperbolic 3-Manifold Kaleidocycle L8a21*. Zenodo. https://doi.org/10.5281/zenodo.20416070

**Information Transformation Law:**
Belmasova, I. Yu. (2026). *Information Transformation Law: Three Transitions, Three Quanta, and the Spiral Structure of Reality*. Zenodo. https://doi.org/10.5281/zenodo.21782683

**Repository:**
Belmasova, I. Yu. (2026). *Kedem-Cycle Ω* [GitHub repository]. https://github.com/Kedem-Cycle-045/Kedem-Cycle-045

## License

MIT License (code). Texts (PDF) — CC BY 4.0.

---

# Kedem-Cycle Ω (Русская версия)

**Kedem-Cycle Ω: Геометрическая теория фундаментальных взаимодействий на основе гиперболического 3-многообразия-калейдоцикла L8a21**

Что если наша Вселенная — не просто система, описываемая математикой, а конкретный геометрический объект из общедоступного каталога SnapPy?

Теория Kedem-Cycle Ω предполагает, что физическая Вселенная соответствует единой геометрической структуре — гиперболическому 3-многообразию-калейдоциклу L8a21. Это замкнутая цепь из десяти тетраэдров, способная к непрерывному вращению без деформации элементов.

Хотя теория сформулирована на языке гиперболических многообразий, геометрия сама по себе не является её фундаментом.

Первичная сущность — информация.

Геометрия — лишь одна из форм её проявления.

В контексте теории информация существует в трёх состояниях:

- геометрическая — застывшая и структурированная;
- физическая — проявленная как материя и взаимодействия;
- живая — накопленная, растущая со временем.

Эти три состояния связаны единым циклом: геометрия проецируется в физику, физика накапливается как живая информация, а накопленное возвращается в геометрию. Но оно не возвращается в исходную точку: каждое возвращение меняет геометрию, поэтому цикл принимает форму спирали.

## Результаты

- Калибровочные группы SU(3)×SU(2)×U(1) с доказательством A₆ → SU(3)
- Массы лептонов, кварков, мезонов и барионов — 28 частиц — со средним отклонением 0.057%
- Семь кандидатов на роль тёмной материи в диапазоне 28–50 ГэВ с уникальным дублетом и расщеплением 31 МэВ
- Массы нейтрино и все три угла смешивания PMNS
- Постоянная тонкой структуры
- Планковская масса и гравитационная постоянная
- Плотность тёмной энергии и барионная асимметрия Вселенной
- Возраст Вселенной и постоянная Хаббла
- Магнитные моменты нуклонов и аномальный магнитный момент электрона
- Пороги звёздной эволюции
- Закон трёхмерной турбулентности
- Квантовая гравитация с квантом энергии E_grav ≈ 2.97 ГэВ
- Правило Борна как теорема
- Коллапс волновой функции как информационная проекция Z → L8a21

## Фальсифицируемые предсказания

Теория фальсифицируема. Она предсказывает:

- семь ψ-резонансов в диапазоне 28–50 ГэВ;
- дублет ψ₃/ψ₄ с расщеплением 31 МэВ;
- резонансы на энергиях n × 2.97 ГэВ.

Если эти сигналы не будут обнаружены, теория должна считаться опровергнутой.

## Структура

- `Kedem-Cycle-v18-EN.pdf` — монография (английская версия, v18)
- `Kedem-Cycle-v18-RU.pdf` — монография (русская версия, v18)
- `_Kedem_Cycle_Omega.pdf` — препринт о массах частиц
- `Information-Transformation-Law.pdf` — Закон трансформации информации
- `CITATION.cff` — метаданные для цитирования
- `LICENSE` — лицензия MIT
- `code/` — Python-код для проверки

## How to run

```bash
pip install -r requirements.txt
python code/code/main.py --verify

## Пример вывода

```bash
$ python main.py --verify
...
```

## Цитирование

Если вы используете эту работу, пожалуйста, цитируйте её так:

**Монография:**
Бельмасова, И. Ю. (2026). *Kedem-Cycle Ω: Геометрическая теория фундаментальных взаимодействий на основе гиперболического 3-многообразия-калейдоцикла L8a21* (Версия 18). Zenodo. https://doi.org/10.5281/zenodo.20364677

**Препринт о массах частиц:**
Бельмасова, И. Ю. (2026). *Массы элементарных частиц из геометрии гиперболического 3-многообразия-калейдоцикла L8a21*. Zenodo. https://doi.org/10.5281/zenodo.20416070

**Закон трансформации информации:**
Бельмасова, И. Ю. (2026). *Закон трансформации информации: три перехода, три кванта и спиральная структура реальности*. Zenodo. https://doi.org/10.5281/zenodo.21782683

**Репозиторий:**
Бельмасова, И. Ю. (2026). *Kedem-Cycle Ω* [GitHub репозиторий]. https://github.com/Kedem-Cycle-045/Kedem-Cycle-045

## Лицензия

MIT License (код). Тексты (PDF) — CC BY 4.0.

  
