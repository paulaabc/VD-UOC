# Ànalisi d'assoliments a Steam 

> Explorant els patrons de compromís dels jugadors a través dels assoliments dels videojocs

Una anàlisi de més de 71,000 jocs de Steam per entendre com els desenvolupadors utilitzen els assoliments com a eina de disseny i compromís dels jugadors.

## Estructura del Repositori

```
📁 steam-achievements-analysis/
├── 📓 notebooks/
│   ├── Descarrega.ipynb      # Descarrega de dades
│   ├── Entrega.ipynb         # Neteja i analisi de dades i creació del dashboard
├── 📊 data/ 
│   └── steam_games.csv                # Dataset principal de jocs de Steam
├── 🌐 dashboard/
│   └── steam_achievements_dashboard.html # Dashboard interactiu final
├── 📄 Readme.md
└── 📜 License
```

### Passos d'Execució
1. **Clona el repositori**
   ```bash
   git clone https://github.com/yourusername/steam-achievements-analysis.git
   cd steam-achievements-analysis
   ```

2. **Executa el notebook**
   - `Entrega.ipynb` # Cal executar tenint els datseta a la mateixa carpeta

3. **Visualitza el dashboard**
   Obre `dashboard/steam_achievements_dashboard.html` en qualsevol navegador web


## Metodologia

### Fonts de Dades
- **Dataset Principal**: 71,429 jocs de Steam (2025)
- **Dataset d'Assoliments**: 1.15M assoliments individuals amb percentatges de finalització
- **Origen**: Kaggle + API de Steam (es necessaria una API key)

### Preguntes de Recerca
1. **Quins tipus de jocs solen tenir més assoliments?**
2. **Hi ha correlació entre el nombre d'assoliments i la seva dificultat mitjana?**
3. **Els jocs amb més categories tenen assoliments més diversos?**
4. **Hi ha diferències entre jocs gratuïts i de pagament?**

## Llicència

Aquest projecte està sota llicència MIT - veure el fitxer [LICENSE](LICENSE) per detalls.

---

