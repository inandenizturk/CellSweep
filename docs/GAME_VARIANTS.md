# Game Variants Guide

CellSweep includes multiple HTML file variants, each designed for different use cases and branding.

## Main Variants

### CellSweep.html
- **Primary version** with SOL cryptocurrency integration
- **Branding**: "Premium CellSweep"
- **Currency**: SOL (Solana)
- **Theme**: Dark gradient (default)
- **Use case**: Main production version

### solana.html
- **Nosana version** with NOS token integration
- **Branding**: "Premium Minesweeper with Nosana Betting"
- **Currency**: NOS (Nosana tokens)
- **Theme**: Purple gradient
- **Use case**: Nosana ecosystem integration

### minegrid.html
- **Alternative branding** version
- **Branding**: "Premium Minesweeper"
- **Currency**: SOL (Solana)
- **Theme**: Purple gradient
- **Use case**: Generic minesweeper branding

### minegrid-competition.html
- **Competition variant** with enhanced features
- **Branding**: "Premium Minesweeper"
- **Currency**: SOL (Solana)
- **Features**: Additional competition mechanics
- **Use case**: Tournament and competition events

### minegrid-progressive-fixed.html
- **Progressive betting** variant
- **Branding**: "Premium Minesweeper"
- **Currency**: SOL (Solana)
- **Features**: Fixed progressive betting system
- **Use case**: Progressive jackpot games

## Key Differences

| Feature | CellSweep.html | solana.html | minegrid.html | competition.html | progressive.html |
|---------|----------------|-------------|---------------|------------------|------------------|
| Currency | SOL | NOS | SOL | SOL | SOL |
| Branding | CellSweep | Nosana | MineGrid | MineGrid | MineGrid |
| Theme | Dark | Purple | Purple | Purple | Purple |
| Special Features | Standard | Nosana integration | Standard | Competition mode | Progressive betting |

## Choosing the Right Variant

### For Production
- Use **CellSweep.html** for the main game experience
- Use **solana.html** for Nosana ecosystem integration

### For Development
- Any variant can be used for testing
- **CellSweep.html** recommended for consistency

### For Custom Deployments
- Modify any variant to match your branding
- Update currency symbols and wallet integration as needed

## Customization

All variants share the same core functionality and can be customized by:

1. **Changing branding** - Update titles and text
2. **Modifying themes** - Adjust CSS color variables
3. **Currency integration** - Update wallet and token handling
4. **Feature toggles** - Enable/disable specific game modes

## Technical Notes

- All variants use the same JavaScript game engine
- Differences are primarily in styling and configuration
- Wallet integration can be swapped between SOL/NOS/other tokens
- Mobile responsiveness is consistent across all variants
