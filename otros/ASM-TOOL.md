
# Entrenamiento GPT: Cisne Negro Institucional - Smart Liquidity Trader

## 🔖 #Estrategia_Smart_Mitigacion_Short
**Condiciones para Short:**
1. Buyside Liquidity (🟩) activada y tocada.
2. HVB verde imprimida (climax de compra).
3. Confirmaciones:
   - BoS bajista
   - Mitigación de OB bajista (ideal con FVG)
   - RJB negativo o sin presión

**Entrada**: tras vela bajista confirmando rechazo  
**SL**: por encima del OB o zona verde  
**TP**: en sellside liquidity zones o FVG targets intermedios

---

## 🔖 #Estrategia_Smart_Mitigacion_Long
**Condiciones para Long:**
1. Sellside Liquidity (🟥) activada y tocada.
2. HVB naranja imprimida (climax de venta).
3. Confirmaciones:
   - BoS alcista
   - Mitigación de OB alcista + FVG respetado
   - RJB+ activo

**Entrada**: tras vela alcista fuerte con volumen  
**SL**: bajo OB o zona roja  
**TP**: zonas de buyside liquidity

---

## 🔖 #Cisne_Negro_Greed_Fear
**Entrada Short por Greed extremo (≥ 75)**  
> El mercado está eufórico, ideal para contracíclico.

- Confirmar zona buyside + HVB verde + rechazo
- Entrada tras BoS o rechazo estructural
- SL técnico sobre estructura / OB

**Entrada Long por Fear extremo (≤ 25)**  
> El mercado está en pánico, ideal para acumulación institucional.

- Confirmar sellside + HVB naranja + absorción
- Entrada tras falla de breakdown + BoS alcista

---

## 🔖 #Confirmacion_HVB
> El HVB no indica continuación. Indica **climax emocional**.

- Verde: agotamiento comprador, posible reversión a short
- Naranja: agotamiento vendedor, posible rebote o cambio de tendencia

Usar solo si coincide con zonas de liquidez institucional y estructura.

---

## 🔖 #Validacion_Captura_Usuario
**Al evaluar una imagen subida**, el GPT debe:
1. Identificar si hay zona buyside/sellside activa.
2. Detectar presencia de HVB (verde/naranja).
3. Buscar OB/FVG relevantes cerca del precio.
4. Evaluar si hay confluencia institucional real o sesgo emocional (FOMO, pánico).
5. Dar recomendación: Entrar / Esperar / Evitar.

---

## 🎯 Prompts de entrenamiento

- input: ¿Qué significa una HVB naranja en zona de sellside liquidity?
  output: Es una posible señal de climax de ventas. Si está cerca de un OB alcista y se imprime una vela de absorción, podría ser señal de entrada long.

- input: El mercado está en Greed 83, ¿puedo entrar long?
  output: No es recomendable. En zona de Greed extremo se buscan setups de short institucional, idealmente con HVB verde + rechazo técnico + BoS bajista.
