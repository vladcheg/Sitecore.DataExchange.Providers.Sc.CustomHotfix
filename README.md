# Hotfixes for Sitecore Provider of Data Exchange Framework 2.0.1
1. Copy `Sitecore.DataExchange.Providers.Sc.CustomHotfix.dll` from source to website bin folder
2. Find `/sitecore/templates/Data Exchange/Providers/Sitecore/Pipeline Steps/Resolve Multilanguage Sitecore Item Dictionary Pipeline Step/__Standard Values` and update processor type field value with `Sitecore.DataExchange.Providers.Sc.CustomHotfix.Processors.PipelineSteps.ResolveMultilanguageSitecoreItemDictionaryPipelineStep,Sitecore.DataExchange.Providers.Sc.CustomHotfix`
3. Find `/sitecore/templates/Data Exchange/Providers/Sitecore/Pipeline Steps/Update Sitecore Item Pipeline Step/__Standard Values` and update processor type field value with `Sitecore.DataExchange.Providers.Sc.CustomHotfix.Processors.PipelineSteps.UpdateSitecoreItemStepProcessor,Sitecore.DataExchange.Providers.Sc.CustomHotfix`

Verify that all existed pipeline steps override the values.
