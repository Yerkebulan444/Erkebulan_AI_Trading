# Erkebulan AI Trading Suite — Handover Guide

## 🔑 Included Files
- Full source code (bots, SaaS, ML model)
- Trained model: `model.pkl`
- Dataset: `signals_dataset.csv`
- Landing page: `/web`
- Auto-launch script: `start_all.sh`
- `.env.example` template

## 🧭 Setup Instructions
1. Install Python 3.11+
2. `python3 -m venv venv && source venv/bin/activate`
3. `pip install -r requirements.txt`
4. Copy `.env.example` → `.env` and add your own tokens:
   - `TELEGRAM_TOKEN`
   - `OPENAI_API_KEY`
   - `CHANNEL_ID`
   - `STRIPE_API_KEY`
5. Run:  
   `./start_all.sh`

## 🧩 Components
- `bot_777sss.py`: Main aggressive trading bot  
- `bot_777sss_impulse_v2.py`: Impulse mode bot  
- `saas_signal_bot.py`: Telegram SaaS management  
- `subscription_bot_stripe.py`: Stripe subscription automation  
- `auto_train.py`: ML auto-learning system  
- `feedback_handler.py`: Telegram trade feedback collection  
- `ai_financial_vision.py`: AI analytics and reporting  
- `signals_dataset.csv`: Data used for ML training  

## 💰 Transfer Process
- Buyer receives the GitHub repository or release archive (.tar.gz)
- Full commercial rights included
- Support: 7 days after handover (installation, configuration)

## 📞 Contact
Erkebulan AI Labs  
Telegram: [@ErkebulanAI_trade](https://t.me/ErkebulanAI_trade)  
GitHub: [Erkebulan444](https://github.com/Yerkebulan444)
