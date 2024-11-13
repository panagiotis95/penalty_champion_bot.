import telebot                                                                                                                                                                                                                   API_TOKEN = (7642358790:AAHVLG8IpKBvqZ4TYfB6ToIjiNSeZ7zDyPU)                                                                                                                                                                      @bot.message_handler(commands=['start'])
def send_welcome(message):
    bot.reply_to(message, "Καλωσήρθες στο Penalty Champion Bot! Είμαι εδώ για να προβλέψω πού θα ρίξεις το πέναλτι!")                                                                                                                @bot.message_handler(commands=['help'])
def send_help(message):
    bot.reply_to(message, "Μπορείς να με ρωτήσεις πού να ρίξεις το πέναλτι και θα προσπαθήσω να σε βοηθήσω!")
    @bot.message_handler(func=lambda message: True)
def echo_all(message):
    bot.reply_to(message, "Πες μου τι θες να προβλέψω!")                                                                                                                                                                             bot.polling()
