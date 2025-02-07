# Filtros FIR e Transformações em Frequência

Este projeto implementa um filtro FIR e explora diferentes transformações em frequência para modificar seu comportamento. O código permite a aplicação de transformações para converter um filtro passa-baixa em outros tipos, como passa-alta, rejeita-faixa e passa-faixa.

## 📌 Funcionalidades
- Implementação de um filtro FIR passa-baixa.
- Transformações em frequência:
  - **Z⁻¹ = -z⁻¹** → Passa-Alta
  - **Z⁻¹ = z⁻²** → Rejeita-Faixa
  - **Z⁻¹ = -z⁻²** → Passa-Faixa
- Visualização da resposta em frequência (magnitude e fase).

## 🚀 Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install numpy matplotlib scipy
   ```
3. Abra o notebook FiltroFIR.ipynb em um ambiente compatível, como Jupyter Notebook ou Google Colab.

## 📊 Resultados
O projeto gera gráficos comparativos mostrando como cada transformação afeta a magnitude e a fase do filtro original.




