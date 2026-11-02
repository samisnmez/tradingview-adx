# TradingView ADX (seviye renkli)

TradingView'un hazır **Directional Movement Index (DMI)** göstergesinden türetilmiş, sade bir ADX göstergesi (Pine Script v6).

*English summary below.*

## Ne yapar

- Yalnız **ADX** çizgisini gösterir (+DI ve −DI çizgileri kaldırıldı).
- ADX seviyenin (varsayılan **20**) **altındayken kırmızı**, **üstündeyken mavi** çizilir.
- 0 ile seviye arası **riskli bölge** olarak hafif mor zeminle işaretlenir; bölgenin sınırları çizgiyle belirtilir.
- Seviye ve tüm renkler gösterge ayarlarından (**Inputs**) değiştirilebilir. ADX hesabı orijinal DMI ile aynıdır.

## Dosyalar

| Dosya | İçerik |
|---|---|
| `adx-modifiye.pine` | Bu gösterge |
| `adx.txt` | Karşılaştırma için TradingView'un orijinal DMI kodu |

## Kurulum

1. TradingView'da alttaki **Pine Editor**'ü aç.
2. `adx-modifiye.pine` içeriğini yapıştır.
3. **Add to chart** (Grafiğe ekle).

## English

A simplified ADX indicator (Pine Script v6) derived from TradingView's built-in DMI: shows only the ADX line, red below the level (default 20) and blue above it, with the 0–level band shaded as a risk zone. Level and colours are configurable in Inputs. Paste `adx-modifiye.pine` into the Pine Editor and add it to the chart. `adx.txt` is the original built-in DMI source, kept for reference.

## Lisans / License

Bu depodaki değişiklikler MIT lisanslıdır, bkz. [LICENSE](LICENSE). Orijinal DMI kodu TradingView'a aittir.
The changes in this repository are MIT licensed. The original DMI code belongs to TradingView.
