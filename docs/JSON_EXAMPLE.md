# Пример клиентского JSON

Каждая метка содержит:

- **timestamp** — таймкод в видео
- **label** — класс состояния
- **tension** — напряжение (0–99%)
- **note** — комментарий эксперта
- **sensors** — данные всех сенсоров в момент метки

## Пример

```json
{
  "video": "test_self.mp4",
  "marks_count": 2,
  "marks": [
    {
      "timestamp": 13.8,
      "label": "MANUAL",
      "tension": 18.4,
      "note": "здесь он соврал про деньги",
      "sensors": {
        "pose_velocity": 0.089,
        "shoulder_tension": 0.02,
        "body_lean": 0.016,
        "blink_rate": 0.0,
        "heart_rate": 75.0,
        "voice_pitch": 0.0,
        "lip_tension": 0.013,
        "brow_knit": 0.041
      }
    }
  ]
}
```
