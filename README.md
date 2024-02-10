<p align="center">
  <img height="25" src="https://api.visitorbadge.io/api/VisitorHit?user=beatsbyluca&countColor=%234a12ba" alt="Profile Views"/>
  <img height="25" src="https://img.shields.io/github/followers/beatsbyluca?color=4a12ba&style=for-the-badge&logo=github&label=Follow" alt="Followers"/>
  <img height="25" src="https://img.shields.io/github/stars/beatsbyluca?color=4a12ba&style=for-the-badge&logo=github&label=Stars" alt="Stars"/>
</p>

```python
from abc import ABCMeta, abstractstaticmethod


class IxKian(metaclass=ABCMeta):
    @abstractstaticmethod
    def contact():
        return ["discord", "telegram"]

    @abstractstaticmethod
    def life():
        return self.coding()

    @abstractstaticmethod
    def coding():
        pass


class Attributes(IxKian):
    @staticmethod
    def contact() -> tuple:
        discord: str = "lucawrld"
        telegram: str = "beatsbyluca"

        return discord, telegram

    @staticmethod
    def life() -> tuple:
        langs = ("German", "English")

        return langs

    @staticmethod
    def coding() -> tuple:
        text_editor = "vscode"
        specialities = ["reverse engineering", "automation"]
        langs = {"pro": "python", "intermediate": "go, c++", "learning": "js"}
        return langs, specialities, text_editor
```
<div style="display: flex; justify-content: center;">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=beatsbyluca&theme=tokyonight" width="30%">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=beatsbyluca&theme=tokyonight" width="30%">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=beatsbyluca&theme=tokyonight&utcOffset=1" width="30%">
</div>
