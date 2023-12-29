from rich import print as rprint
from rich.prompt import Prompt
list=[0,1]
while True:
    n = int(Prompt.ask('[bold green]enter a no. > 2:[/bold green]'))
    try:
      if n > 2:
        for i in range(2, n):
          list.append(list[i-1] + list[i-2])
        rprint(list)
        break
      elif n== 1 or 0:
        rprint('enter greater than 2')
        continue
      else:
        rprint('pls enter a valid no.')
        continue
    except ValueError:
      rprint('enter a no. not any other mathematical logic')
      continue

