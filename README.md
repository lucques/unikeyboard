unikeyboard
===========
xkb keyboard layout with 8 levels for often used unicode characters


Features: 
----------
* almost unchanged german keyboard layout (level 1 + 2)
* greek alphabet (level 3 + 4)
* typographical characters (level 3 + 4) like — „ “ ” …
* math symbols (level 5 – 7) like ∂ ∑ ∫ ∈ ℕ
* special characters (level 8)


The layout
----------

	Level 1 – 4:
	┌─────┐ Level1: ⟨key⟩                           normal (except #)
	│ 2 4 │ Level2: Shift + ⟨key⟩                   normal (except § und ')
	│ 1 3 │ Level3: AltGr + ⟨key⟩                   greek1 + typography1
	└─────┛ Level4: AltGr + Shift + ⟨key⟩           greek2 + typography2

	┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━━━┓  ┌─────┬─────┬─────┬─────┐
	│ ° ⁰ │ ! ‚ │ " ’ │ ' ‘ │ $ ¥ │ % ₨ │ &   │ / ⁅ │ ( ⟨ │ ) ⟩ │ = ⁆ │ ? ß │ ` ¨ ┃Backspace  ┃  │     │ /   │ *   │ -   │
	│ ^ C │ 1 „ │ 2 “ │ 3 ” │ 4 € │ 5 £ │ 6   │ 7 { │ 8 [ │ 9 ] │ 0 } │ ß \ │ ´   ┃           ┃  │     │ /   │ *   │ -   │
	┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━━━┫  ├─────┼─────┼─────┼─────┤
	┃       ┃ Q   │ W   │ Ε € │ R ϱ │ T   │ Z   │ U Θ │ I   │ O Ω │ P Π │ Ü ▪ │ * ± ┃Enter    ┃  │ ⚠   │ ⚡   │ ⚑   │     │
	┃Tab    ┃ q @ │ w   │ e ε │ r ρ │ t τ │ z ζ │ u θ │ i i │ o ω │ p π │ ü ' │ + ~ ┃         ┃  │ 7   │ 8   │ 9   │     │
	┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┲━━━━┻┓        ┃  ├─────┼─────┼─────┤     │
	┃Caps    ┃ A Α │ S Σ │ D Δ │ F Φ │ G Γ │ H   │ J   │ K   │ L Λ │ Ö † │ Ä ‡ ┃Caps ┃        ┃  │ ☮   │ ♻   │ ☢   │ +   │
	┃Lock    ┃ a α │ s σ │ d δ │ f φ │ g γ │ h η │ j   │ k κ │ l λ │ ö § │ ä # ┃Lock ┃        ┃  │ 4   │ 5   │ 6   │ +   │
	┣━━━━━━━┳┹────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┲┻━━━━━┻━━━━━━━━┫  ├─────┼─────┼─────╆━━━━━┪
	┃       ┃ > ‖ │ Y Ψ │ X Ξ │ C   │ V   │ B   │ N   │ Μ   │ ; ‣ │ : · │ _ — ┃               ┃  │ ☹   │ ☺   │ ♥   ┃Enter┃
	┃Shift  ┃ < | │ y ψ │ x ξ │ c χ │ v   │ b β │ n ν │ m μ │ , • │ . … │ - – ┃Shift          ┃  │ 1   │ 2   │ 3   ┃     ┃
	┣━━━━━━━╋━━━━━┷━┳━━━┷━━━┱─┴─────┴─────┴─────┴─────┴─────┴──┲━━┷━━━━┳┷━━━━━┻┳━━━━━━━┳━━━━━━┫  ├─────┴─────┼─────┨     ┃
	┃       ┃       ┃       ┃                                  ┃       ┃       ┃       ┃      ┃  │ ␣         │     ┃     ┃
	┃Ctrl   ┃Meta   ┃Alt    ┃              Space               ┃AltGr  ┃Meta   ┃Menu   ┃Ctrl  ┃  │ 0         │     ┃     ┃
	┗━━━━━━━┻━━━━━━━┻━━━━━━━┹──────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┻━━━━━━┛  └───────────┴─────┺━━━━━┛

	Level 5 – 8:
	┌─────┐ Level5: Caps + ⟨key⟩                    math1 
	│ 6 8 │ Level6: Caps + Shift + ⟨key⟩            math2 (invertiert or expands math1)
	│ 5 7 │ Level7: Caps + AltGr + ⟨key⟩            math3 or symbols
	└─────┛ Level8: Caps + AltGr + Shift + ⟨key⟩    alternative characters

	┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━━━┓  ┌─────┬─────┬─────┬─────┐
	│ ⁰   │ ¹ ′ │ ² ″ │ ³ ‴ │ ⁴   │ ⁵ ‰ │ ⁶ ♂ │ ⁷   │ ⁸ ⌈ │ ⁹ ⌉ │ ≈ ∅ │ ⁻   │°    ┃Backspace  ┃  │     │     │     │     │
	│ ₀ C │ ₁ ¬ │ ₂ ½ │ ₃ ¾ │ ₄ ¼ │ ₅   │ ₆ ♀ │ ₇ ÷ │ ₈ ⌊ │ ₉ ⌋ │ ≠ ≡ │ ⁺   │¸  ¯ ┃           ┃  │     │     │     │     │
	┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━━━┫  ├─────┼─────┼─────┼─────┤
	┃       ┃ ⌀   │ ∛   │ ∉ ⊊ │   R │ ⊥ ™ │   z │   ϑ │ ∬ J │ ∬   │ ∝   │     │ ±   ┃Enter    ┃  │ ⇕   │ ⇑   │     │     │
	┃Tab    ┃ ℚ   │ √   │ ∈ ⊆ │ ℝ   │ ⊤   │ ℤ   │ ∞   │ ∫ ∭ │ ∫ ∭ │ ∏   │ ∝   │ ⋅   ┃         ┃  │ ↕ ┌ │ ↑ ┬ │   ┐ │     │
	┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┲━━━━┻┓        ┃  ├─────┼─────┼─────┤     │
	┃Caps    ┃ ∠ Å │   ſ │ ∇   │ F ϕ │ ∁   │ ∩ ℏ │ ∪   │ ⊖ ⊙ │ L ℓ │ ⇔ ↷ │ ⇒   ┃Caps ┃        ┃  │ ⇐   │ –   │ ⇒   │     │
	┃Lock    ┃ ∠   │ ∑   │ ∂ ⌀ │ ƒ F │ ¬   │ ∧ ♮ │ ∨   │ ⊕ ⊗ │ –   │ ↔ ↶ │ → ↦ ┃Lock ┃        ┃  │ ← ├ │ ★ ┼ │ → ┤ │   │ │
	┣━━━━━━━┳┹────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┲┻━━━━━┻━━━━━━━━┫  ├─────┼─────┼─────╆━━━━━┪
	┃       ┃ < ☐ │ > ☑ │ ϵ ☒ │ ∁ © │ .⃗   │ ∄   │ ∇ N │ ⊢   │ ⊢   │ ∕   │ ∓ ― ┃               ┃  │ ⇔   │ ⇓   │ ⇋   ┃Enter┃
	┃Shift  ┃ ≤   │ ≥ ✔ │ × ✘ │ ℂ C │ ∀   │ ∃ ♭ │ ℕ ♯ │ ⊢   │ ⊢   │ ⋅   │ − ‑ ┃Shift          ┃  │ ↔ └ │ ↓ ┴ │ ⇌ ┘ ┃     ┃
	┣━━━━━━━╋━━━━━┷━┳━━━┷━━━┱─┴─────┴─────┴─────┴─────┴─────┴──┲━━┷━━━━┳┷━━━━━┻┳━━━━━━━┳━━━━━━┫  ├─────┴─────┼─────┨     ┃
	┃       ┃       ┃       ┃                                  ┃       ┃       ┃       ┃      ┃  │ ‰         │ ′   ┃     ┃
	┃Ctrl   ┃Meta   ┃Alt    ┃              Space               ┃AltGr  ┃Meta   ┃Menu   ┃Ctrl  ┃  │ % ─       │ ,   ┃     ┃
	┗━━━━━━━┻━━━━━━━┻━━━━━━━┹──────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┻━━━━━━┛  └───────────┴─────┺━━━━━┛
