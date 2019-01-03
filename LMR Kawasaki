import discord
from discord.ext.commands import Bot
from discord.ext import commands
import asyncio
import time
import random
from discord import Game


Client = discord.client
client = commands.Bot(command_prefix = '!')
Clientdiscord = discord.Client()


@client.event
async def on_ready():
    await client.change_presence(game=Game(name='Mx Simulator'))
    print('Ready, Freddy') 


@client.event
async def on_message(message):
    if message.content == '!teamlink':
        await client.send_message(message.channel,'https://drive.google.com/file/d/1VnrUk8LN3nSIH0RMmsa0asaX55K5_psX/view?usp=sharing')
    if message.content == '!teampost':
        await client.send_message(message.channel,'https://forum.mxsimulator.com/viewtopic.php?f=6&t=51116')
    if message.content == '!teamlogo':
        em = discord.Embed(description='')
        em.set_image(url='https://i.imgur.com/EaoB6eX.png')
        await client.send_message(message.channel, embed=em)
    if message.content == '!teamrender':
        em = discord.Embed(description='')
        em.set_image(url='https://i.imgur.com/CXBV7Lx.png')
        await client.send_message(message.channel, embed=em)
client.run('NTMwNDM5OTQ2NzAwNTg3MDA4.Dw_aeg.2VlTtD545-nUUydavlokOFOFiG4')

