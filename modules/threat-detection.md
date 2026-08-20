# Threat Detection Module

Identifies and categorizes competitive threats, applying an explicit scoring model.

## Threat Categories
1. **Product Threat**: Rival features weaken differentiation.
2. **Pricing Threat**: Rival undercuts pricing.
3. **Distribution Threat**: Rival wins critical channel partnerships.
4. **Brand Threat**: Rival captures category mindshare.
5. **Customer Threat**: Rival targets core customer segments.
6. **Technology Threat**: Rival shifts technology stack (improving economics).

## Threat Scoring
Threat score prioritizes alerts objectively:
$$\text{Threat Score} = \text{Impact} \times \text{Probability} \times \text{Proximity} \times \text{Confidence}$$

- **Impact**: 1-5 (low damage to existential risk)
- **Probability**: 1-5 (highly unlikely to highly certain)
- **Proximity**: 1-5 (long-term possibility to imminent event)
- **Confidence**: 0.1 to 1.0 (based on Evidence Confidence)
