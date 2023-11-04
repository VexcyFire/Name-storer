import discord
from discord.ext import commands

client = commands.Bot(command_prefix = "?", intents=discord.Intents.all())

@client.event
async def on_ready():
    print("This bot is now ready")
    print("---------------------")



#######################################
#########################################
#############################################
################################################


@client.command()
async def A (ctx):
    await ctx.send("")

@client.command()
async def B (ctx):
    await ctx.send("")

@client.command()
async def C (ctx):
    await ctx.send("")

@client.command()
async def D (ctx):
    await ctx.send("")

@client.command()
async def E (ctx):
    await ctx.send("")

@client.command()
async def F (ctx):
    await ctx.send("")

@client.command()
async def G (ctx):
    await ctx.send("")

@client.command()
async def H (ctx):
    await ctx.send("")

@client.command()
async def I (ctx):
    await ctx.send("")

@client.command()
async def J (ctx):
    await ctx.send("")

@client.command()
async def K (ctx):
    await ctx.send("")

@client.command()
async def L (ctx):
    await ctx.send("")

@client.command()
async def M (ctx):
    await ctx.send("")

@client.command()
async def N (ctx):
    await ctx.send("")

@client.command()
async def O (ctx):
    await ctx.send("l")

@client.command()
async def P (ctx):
    await ctx.send("")
    
@client.command()
async def Q (ctx):
    await ctx.send("")

@client.command()
async def R (ctx):
    await ctx.send("")

@client.command()
async def S (ctx):
    await ctx.send("")

@client.command()
async def T (ctx):
    await ctx.send("")

@client.command()
async def U (ctx):
    await ctx.send("")

@client.command()
async def V (ctx):
    await ctx.send("")

@client.command()
async def W (ctx):
    await ctx.send("")

@client.command()
async def X (ctx):
    await ctx.send("")

@client.command()
async def Y (ctx):
    await ctx.send("")

@client.command()
async def Z (ctx):
    await ctx.send("")

@client.event
async def on_member_join(member):
    await member.send("")

#############################################################

client = commands.Bot(command_prefix = "!", intents=discord.Intents.all())

@client.command()
async def Help (ctx):
    await ctx.send("Type !Uses or type !Tos for Help in the terms and service of the bot")


@client.command()
async def Uses (ctx):
    await ctx.send("This bot uses ? to get results for gamertags and can be used for storing names or wages but the main purpose fo this bot is for quick easy checks of blacklisted names")


@client.command()
async def Tos (ctx):
    await ctx.send("This bot is to be used for personal use and should not be used for malicious purposes")

client.run('')
