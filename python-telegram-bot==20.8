import os
from telegram import Update, InlineKeyboardButton, InlineKeyboardMarkup
from telegram.ext import ApplicationBuilder, CommandHandler, CallbackQueryHandler, ContextTypes

BOT_TOKEN = os.getenv("BOT_TOKEN")

async def start(update: Update, context: ContextTypes.DEFAULT_TYPE):
    keyboard = [[InlineKeyboardButton("🔹 Rotator Cuff Repair", callback_data='rotator')]]
    reply_markup = InlineKeyboardMarkup(keyboard)
    await update.message.reply_text("👋 ברוך הבא! בחר ניתוח:", reply_markup=reply_markup)

async def handle_button(update: Update, context: ContextTypes.DEFAULT_TYPE):
    query = update.callback_query
    await query.answer()

    if query.data == 'rotator':
        msg = """🦾 ניתוח: Rotator Cuff Repair

🧼 הרדמה:
- עגלת בלוק (חניה)
- אולטרסאונד (חניה)

🛏️ ציוד בחדר:
- מיטת כתף
- מגדל ארטרוסקופיה (מחסן חדר 2)
- סקשיין גדול כתף
- חגורת ספוג כחולה (חדר יקרים)
- עגלת תמיסות - NS 3 ליטר
- BAIR HUGGER
- שרוול TRIMANO (חדר יקרים)
- VAPR (ארון חכם)
- שייבר (ארון חכם)

🧰 ציוד להשכבה:
- חגורת ספוג כחולה
- רולת פד כחול
- U DRAPE
- אגד אלסטי רחב

📦 רשתות:
- רשת עוגנים כתף
- אופטיקה 30° 4 מ"מ קצרה
- רשת שייבר
- זרוע TRIMANO (מחסן חדר 2)

🏥 מהמחסן:
- חלוקים XL
- קערות
- רחצה
- קיט ארטרוסקופיה
- קיט חבישה - אורתופדיה
- כיסוי כתף
- מגבות סטריליות

🩹 חבישה:
- פד כחול
- TENSOPLAST"""
        await query.edit_message_text(msg)

if __name__ == '__main__':
    app = ApplicationBuilder().token(BOT_TOKEN).build()
    app.add_handler(CommandHandler("start", start))
    app.add_handler(CallbackQueryHandler(handle_button))
    app.run_polling()
