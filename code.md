
import disnake
from disnake.ext import command
bot=commands.Bot()
@bot.slash_command()
async def ping(interaction):
    await interaction.response.send_message("Pong!")
bot.run("TOKEN HERE")
