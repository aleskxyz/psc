# Position Size Calculator

This is a simple **Position Size Calculator** designed to help traders calculate the appropriate position size based on risk, entry price, and stop loss. It uses a basic formula:

```
Position Size = Risk / (Entry Price - Stop Loss)
```

The calculator will display the result with 4 decimal precision and color the result either green (for long trades) or red (for short trades). The result is also copyable with a click.

## Features

- **Risk, Entry Price, and Stop Loss input fields**
- **Real-time calculation** of position size
- **Copy result to clipboard** by clicking the result
- **Responsive UI** designed with Bootstrap
- **Colors the result** green for long trades and red for short trades

## Usage

1. **Enter the risk amount** in the "Risk Amount" field.
2. **Enter your entry price** and **stop loss** in their respective fields.
3. Click **Calculate** or press **Enter** to compute the position size.
4. The result will appear in a colored box. **Green** if the entry is larger than the stop loss (Long), and **Red** if the stop loss is larger (Short).
5. You can **click the result** to copy it to the clipboard.

## Technologies Used

- HTML
- CSS (Bootstrap)
- JavaScript (Vanilla)

## Hosting

This project is hosted using **GitHub Pages**, making it available online at:

https://aleskxyz.github.io/psc

