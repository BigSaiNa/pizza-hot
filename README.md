# pizza-hot
import discord
from discord.ext import commands

bot_token = 'MTAzMjg1NzEwODY0OTA5MTIxMw.GfQM9w.ax8RcxF2Vz8Su5TsXA1UPRZ5UyV7H6d_knr9cY'
bot = commands.Bot(command_prefix = 'eat' , intents=discord.Intents.all())

@bot.event
async def on_ready():
    print('your pizza is ready!!!')

bot.run(bot_token)
