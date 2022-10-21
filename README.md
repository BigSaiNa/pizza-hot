# pizza-hot
import discord
from discord.ext import commands

bot_token = ''
bot = commands.Bot(command_prefix = 'eat' , intents=discord.Intents.all())

@bot.event
async def on_ready():
    print('your pizza is ready!!!')

bot.run(bot_token)
