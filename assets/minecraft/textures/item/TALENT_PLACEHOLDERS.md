# Talent UI textures (placeholders)

Toutes les textures `talent_*.png` sont des **placeholders 32×32**.
Remplace simplement le fichier PNG du même nom — les models JSON et `items/paper.json` sont déjà branchés.

## Sets

| Préfixe | Usage |
|---------|--------|
| `talent_slot_*` | Fond de grille / bordure chrome |
| `talent_path_h/v_*` | Segments horizontaux / verticaux |
| `talent_path_corner_*` | Coudes NE/NW/SE/SW (+ `_lit`) |
| `talent_path_t_*` / `talent_path_cross_*` | Placeholders futurs (jonctions T / croix) |
| `talent_arrow_*` | Navigation + retour |
| `talent_info` | Bouton info |
| `talent_node_locked/available/unlocked/max` | États génériques |
| `talent_node_root` | Racine décorative |
| `talent_node_generic` | Icône générique pour futurs arbres |
| `talent_node_<skill>` | Icônes caster (vitality, arcane, …) |

Régénérer les placeholders :

```bash
python scripts/gen_talent_placeholders.py
```
