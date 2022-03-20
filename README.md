        function()
            for i, v in next, getgc(true) do
                if type(v) == "table" and rawget(v, "damage") then
                    v.bloomFactor = 0
                    v.noYawRecoil = "true"
                    v.recoilCoefficient = 1
                end
            end
        end
    end
