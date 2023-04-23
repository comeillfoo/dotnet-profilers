# dotnet-profilers

Способы мониторинга производительности .NET-приложений.

## Описание подмодулей

- [ManagedDotnetProfiler](https://github.com/comeillfoo/ManagedDotnetProfiler) - форк одноименного [проекта](https://github.com/kevingosse/ManagedDotnetProfiler), попытка приспособить проект в полноценный инструмент мониторинга,
- [self-profiler](https://github.com/comeillfoo/self-profiler) - попытка использование средства пространства имен `System.Diagnostics` для мониторинга производительности,
- [log-plotter](https://github.com/comeillfoo/log-plotter) - вспомогательный инструмент для отрисовки графиков по трассировке (логам) событий, получаемые от `self-profiler`,
- [visual-clr](https://github.com/comeillfoo/visual-clr) - конечный инструмент для мониторинга производительности, использующий `Profiling API`.